# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/profile-card-challenge-using-flexbox-J_Y31h_ik)
- Live Site URL: [GitHub Page](https://ax-cd.github.io/profile-card-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to place several images in the background property.


```css
body {
    background: url(images/bg-pattern-top.svg) no-repeat scroll -50rem -37rem, url(images/bg-pattern-bottom.svg) no-repeat scroll 10rem 12rem;
    background-color: hsl(185, 75%, 39%);
}
@media (min-width: 37.5em) {
    body {
        background: url(images/bg-pattern-top.svg) no-repeat scroll -17rem -35rem, url(images/bg-pattern-bottom.svg) no-repeat scroll 44rem 20rem;
        background-color: hsl(185, 75%, 39%);
    }
}
```

### Continued development

- Be more comfortable combining several values when using super properties such as background.


### Useful resources

- [background - MDN Web Docs](https://developer.mozilla.org/fr/docs/Web/CSS/background) - Helped to understand how to combine various values in the background property.
- [background-position - MDN Web Docs](https://developer.mozilla.org/fr/docs/Web/CSS/background-position) - Helped with the different syntaxes of the background-position property.


## Author

- Website - [Ax-coding](https://axcoding.blogspot.com/)
- Frontend Mentor - [@Ax-cd](https://www.frontendmentor.io/profile/Ax-cd)
- Instagram - [@ax.coding](https://www.instagram.com/ax.coding/)
