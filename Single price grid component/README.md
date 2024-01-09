# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/responsive-single-grid-price-component-using-grid-sldT3ekVRk)
- Live Site URL: [Live site URL](https://fancy-dasik-0d72aa.netlify.app/single%20price%20grid%20component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have learnt a new concept of using `grid-template-rows` and `grid-template-colums` and also the **media query** usage to make the container responsive

```css
.container {
  display: grid;
  grid-template-rows: repeat(2, minmax(1fr, max-content));
  grid-template-columns: repeat(2, 1fr);
}

@media only screen and (max-width: 650px) {
  .container {
    width: 31rem;
    grid-template-rows: repeat(3, minmax(max-content, 1fr));
    grid-template-columns: 1fr;
  }
}
```

### Useful resources

- [Grid Docs - W3Schools](https://www.w3schools.com/css/css_grid.asp) - Used this for basics syntax
- [Grid template colums - w3Schools](https://www.w3schools.com/css/css_grid_container.asp)

## Author

- Frontend Mentor - [@madhavan-ts](https://www.frontendmentor.io/profile/madhavan-ts)
