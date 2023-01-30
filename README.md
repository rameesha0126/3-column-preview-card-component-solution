# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot 

[Mobile View](https://github.com/rameesha0126/3-column-preview-card-component-solution/blob/master/mobile-view.png)
[Desktop View](https://github.com/rameesha0126/3-column-preview-card-component-solution/blob/master/desktop-view.png)

### Links

- Solution URL: [Solution](https://github.com/rameesha0126/3-column-preview-card-component-solution)
- Live Site URL: [Live site URL](https://rameesha0126.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Using media query to change desktop view and mobile view.

```html
<main class="background">
      <div class="card-component">
```
```css
@media only screen and (min-width: 600px){
    .card-component {
        max-width: 1440px;
        display: flex;
        flex-direction: row;
        padding: 1rem;
    }
```

### Continued development

- Using grid to create responsive grid view. 

### Useful resources

- [W3schools CSS Tutorial](https://www.w3schools.com/css/default.asp)

## Author

- Github - [Rameesha0126](https://github.com/rameesha0126)
- Frontend Mentor - [@rameesha0126](https://www.frontendmentor.io/profile/rameesha0126)
