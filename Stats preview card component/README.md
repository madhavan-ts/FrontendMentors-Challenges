# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-using-flexbox-eEfXQnCVRJ)
- Live Site URL: [Live site URL](https://tubular-tapioca-8c6da0.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I have learnt about the `backgound-blend-mode` and also the `filter` properties and also to make the overlay on the image I used the `::before` pesudo selector

```css
.card__img-container::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  filter: brightness(80%);
  background-color: hsla(277, 64%, 61%, 0.5);
}
```

### Useful resources

- [filter property - MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/filter) - This helped for the `filter` property.
- [overlay using ::before](https://community.hubspot.com/t5/CMS-Development/Adding-a-colour-overlay-to-an-image/m-p/780238#:~:text=To%20add%20a%20color%20overlay,a%20semi%2Dtransparent%20background%20color.&text=In%20this%20code%2C%20the%20%3A%3A,element%20is%20added%20to%20the%20.)

## Author

- Frontend Mentor - [@madhavan-ts](https://www.frontendmentor.io/profile/madhavan-ts)
