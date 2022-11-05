# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshots](#screenshots)
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

### Screenshots

![](./images/desktop-screenshot.png)
![](./images/mobile-screenshot.png)

### Links

- Solution URL: [Frontendmentor.io](https://www.frontendmentor.io/solutions/stats-preview-card-component-using-html-css-bH8XiJiik3)
- Live Site URL: [fsuropaty.github.io](https://fsuropaty.github.io/stats-preview-card-component-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Grid ordering
- Changing an image using background-image in different screen sizes
- Image filter using CSS

```css
.image-container {
  margin: 0;
  padding: 0;
  height: 16em;
  background-color: var(--Soft-violet);
  background-blend-mode: multiply;
}

.image {
  background-color: var(--Soft-violet);
  background-image: url("/images/image-header-mobile.jpg");
  background-size: cover;
  height: 100%;
  opacity: 0.8;
  background-blend-mode: multiply;
}

@media only screen and (min-width: 768px) {
  .image-container {
    order: 2;
    height: 100%;
  }

  .image {
    background-image: url("/images/image-header-desktop.jpg");
  }
}
```

### Useful resources

- [W3Schools](https://www.w3schools.com) - Pretty much your guidebook in website development
- [MDN](https://developer.mozilla.org) - W3Schools but from Mozilla.
- [Codepen.io](https://codepen.io) - Helped me a lot how to do a form validation

## Author

- Website - [fsuropaty](https://www.fsuropaty.github.io)
- Frontend Mentor - [@fsuropaty](https://www.frontendmentor.io/profile/fsuropaty)
