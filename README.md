# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Mobile

![](./images/mobile-screenshot.png)

Desktop

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS
- Flexbox

### What I learned

Ive learned how to change background image depending if you are using a desktop or a mobile device using css. The code is stated below. And you have the link where I found a solution for the problem that occured for me.

```css
.image {
  height: 450px;
  width: 50%;
  border-radius: 10px 0 0 10px;
  background-image: url(./images/image-product-desktop.jpg);
  background-position: center;
  background-size: contain;
}

@media screen and (max-width: 600px) {
  .card {
    flex-direction: column;
    max-width: 340px;
    height: 100%;
  }

  .image {
    width: 100%;
    height: 240px;
    background-image: url(./images/image-product-mobile.jpg);
    background-position: center;
    background-size: cover;
    border-radius: 10px 10px 0 0;
    margin-top: 30px;
  }

  .info {
    width: 100%;
    border-radius: 0 0 10px 10px;
  }
}
```

### Useful resources

- [How to change image based on screen size](https://www.codegrepper.com/code-examples/css/how+to+change+image+based+on+screen+size) - This link learned me how to change background image dependent on screen size using css with breakpoints.

## Author

Andreas Larssamils

- Frontend Mentor - [@andreaslarssamils](https://www.frontendmentor.io/profile/andreaslarssamils)

## Acknowledgments

Thank you Frontendmentor
