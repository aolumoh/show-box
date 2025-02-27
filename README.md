# ShowBox

Welcome to our streaming website project, where we aim to create an immersive and enjoyable streaming experience akin to popular platforms like Netflix. This README serves as a guide to understanding the project structure, functionality, and how to set it up locally.

## Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Contributing](#contributing)

## Introduction

Our streaming website project is designed to provide users with a seamless streaming experience, allowing them to discover, watch, and enjoy a wide range of content including movies, TV shows, documentaries, and more. With a user-friendly interface and a vast library of content, we aim to cater to diverse preferences and interests.

## Technologies Used

- _Frontend_: HTML5, CSS3, JavaScript
- _Version Control_: Git, GitHub
- VS-code

## Contributions

Manpreet kaur
contact: click [here](https://github.com/dhillxnm)

Abdulmalik Olumoh
contact: click [here](https://github.com/aolumoh)

Martins Aleogho
contact: click [here](https://github.com/matineno)

Nishat Samanta Progga
contact: click [here](https://github.com/samanthaprogga)

## Javascript(pop-up)

```Javascript (popup signin)
function hideDialog() {
  dialog.classList.remove('isvisible');
  overlay.classList.remove('isvisible');
  isVisible = false;
}

onEvent('load', window, function() {
  clearForm();
});

onEvent('click', contact, function() {
  showDialog()
});

onEvent('click', overlay, function() {
  if (isVisible) hideDialog();
});

onEvent('keyup', document, function(event) {
  if (isVisible && event.key === 'Escape') {
    hideDialog();
  }
});

onEvent('click', button, function() {
  alert.classList.add('isvisible');
  hideDialog();
  setTimeout(function() {
    alert.classList.remove('isvisible');
    clearForm();
  }, 5500);
});

```

To see live demo click [here](https://dhillxnm.github.io/show-box/)
