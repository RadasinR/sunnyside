# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![firefox](./screenshotDesktop.png)
![firefox](./screenshotMobile.png)

### Links

- Solution URL: [github](https://github.com/RadasinR/sunnyside.git)
- Live Site URL: [live_site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
How to make a menu with CSS only.

```css
.nav-bar__menu {
   position: relative;
}
.nav-bar__list {
   position: absolute;
   display: none;
   list-style: none;
   background-color: var(--WHITE);
   color: var(--DARK-MODERATE-CYAN);
   background-color: var(--WHITE);
   top: 200%;
   right: 10%;
   padding: 4rem 50%;
   flex-direction: column;
   justify-content: flex-start;
   align-items: center;
   gap: 3rem;
}
:is(.nav-bar__menu:hover, .nav-bar__menu:focus-within) .nav-bar__list {
   display: flex;
   width: 90vw;
   border-right: 20px solid transparent;
   border-top: 20px solid #3ebfff;
}
```

## Author

- Frontend Mentor - [@Radasin](https://www.frontendmentor.io/profile/Radasin)
