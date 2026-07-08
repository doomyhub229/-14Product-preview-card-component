# Frontend Mentor - Product Preview Card Component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (Responsive Design for Mobile and Desktop).
- See hover and active states for all interactive elements on the page (like the Add to Cart button).

### Screenshot

![Solution Screenshot](./images/screenshot.png)

### Links

- Solution URL: [My Code on GitHub](https://github.com/doomyhub229/-14Product-preview-card-component)
- Live Site URL: [Live Website on GitHub Pages](https://doomyhub229.github.io/-14Product-preview-card-component/)

## My process

### Built with

- Semantic **HTML5** markup
- Native `<picture>` tag for responsive image optimization
- CSS custom properties (**CSS Variables**)
- **CSS Grid** (used for overall layout centering and the card's 2-column layout)
- **Flexbox** (used inside the card text container for layout distribution)
- Mobile-first approach using relative units (`rem`)

### What I learned

During this project, I significantly improved my skills in responsive web design and modern layout structures. Here is a summary of the core concepts I mastered:

* **Perfect Alignment:** I learned how to achieve clean vertical and horizontal centering using CSS Grid combined with a full-viewport height wrapper.
  ```css
  main {
      display: grid;
      place-items: center;
      min-height: 100vh;
  }
* Mobile-First Responsiveness: I successfully built a layout that adapts seamlessly from a single-column structure on mobile screens (max-width: 425px) to a fluid two-column grid on desktop.

* Asset Optimization: I learned how to use the native HTML <picture> element to serve different images depending on the user's screen size, saving mobile data and improving performance.

<picture>
  <source media="(max-width: 425px)" srcset="./images/image-product-mobile.jpg">
  <img src="./images/image-product-desktop.jpg" alt="Product Image">
</picture>

* Tactile Interactions: I enhanced the User Experience (UX) by removing default button styles and applying smooth transition effects for the :hover and :active states to simulate a real button press.

## Author

* **GitHub** - [@doomyhub229](https://github.com/doomyhub229)
* **Frontend Mentor** -  [@doomyhub229](https://www.frontendmentor.io/profile/doomyhub229)
