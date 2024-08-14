# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- CSS Grid
- Mobile-first workflow
- [Bootstrap](https://getbootstrap.com/) - JS library

### What I learned

```picture``` element

```
<picture>
    <source srcset="images/image-product-desktop.jpg" media="(min-width: 768px)">
    <img class="img-fluid" src="images/image-product-mobile.jpg" alt="A description of the image.">
</picture>
```

it will display image with name of ```image-product-mobile.jpg``` until min width of viewport 768px
then it will switch to ```image-product-desktop.jpg```

### Useful resources

- [Picture element](https://web.dev/learn/design/picture-element/) - This helped me to learn responsive images
