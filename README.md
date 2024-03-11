# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/my-solution.png)

### Links

- Live Site URL: [Huddle landing page](https://jdrodriguez2707.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google fonts](https://fonts.google.com/) - Font library
- [Font awesome](https://fontawesome.com/) - Icon library

### What I learned

- How to add and edit background images:

```css
body {
  background-color: var(--primary-background-color);
  background-image: url("../images/bg-mobile.svg");
  background-repeat: no-repeat;
  background-size: 100%;
}
```

- How to set the same hover effect to two elements to activate it at the same time:

```css
.icon-border:hover {
  border-color: var(--secondary-color);
}

.icon-border:hover .fa-brands {
  color: var(--secondary-color);
}
```

![](./images/hover-effect.jpg)

### Continued development

- Responsive design (specially with images)

- Build websites faster

- Always avoid seeking perfection

### Useful resources

- [The W3C Markup Validation Service](https://validator.w3.org/) - This helped me check the markup validity in my HTML document.
- [The W3C CSS Validation Service - Jigsaw](https://jigsaw.w3.org/css-validator/) - This helped me validate my CSS style sheet.
- [CSSmatic](https://www.cssmatic.com/box-shadow) - This helped me add shadow to the registration button.

## Author

- Frontend Mentor - [@jdrodriguez2707](https://www.frontendmentor.io/profile/jdrodriguez2707)
- Twitter - [@Johan79854000](https://twitter.com/Johan79854000)

## Acknowledgments

I was able to carry out this project thanks to the knowledge I acquired on the [Platzi learning platform 💚](https://platzi.com/new-home/). I want to thank the entire Platzi team and their students who helped me when I had any questions.
