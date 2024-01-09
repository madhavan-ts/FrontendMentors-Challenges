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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/order-summary-component-using-flexbox-MOUhq9r3aw)
- Live Site URL: [Live site URL](https://fancy-dasik-0d72aa.netlify.app/product%20preview%20card%20component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Responsive images in HTML and here is an example to use it.

```html
<picture>
  <source
    srcset="./images/image-product-mobile.jpg"
    media="(max-width:600px)"
  />
  <img
    class="card__image"
    src="./images/image-product-desktop.jpg"
    alt="porduct-img"
  />
</picture>
```

### Useful resources

- [Picture Element in HTML](https://www.w3schools.com/html/html_images_picture.asp) - This helped me for the responsive images without using the `backgound-image` propery in HTML reason.
- [Responsive images](https://www.w3schools.com/css/css_rwd_images.asp#:~:text=The%20HTML%20Element&text=The%20most%20common%20use%20of,nicely%20fill%20the%20browser%20viewport.) - This helped other aspects of using media query for switching between images in HTML.

## Author

- Frontend Mentor - [@madhavan-ts](https://www.frontendmentor.io/profile/madhavan-ts)
