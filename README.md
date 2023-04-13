# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./solution.png) 

### Links

- [Solution](https://github.com/ryanthayes/fem-clipboard-landing-page)
- [Live URL](https://ryanthayes.github.io/fem-clipboard-landing-page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I used a tip I learned from Kevin Powell tutorial trying to experiment with Grids instead of always using Flex. His tip on setting up even columns using 'grid-auto-flow' came in handy.
```css
  .even-columns {
        display: grid;
        grid-auto-flow: column;
        grid-auto-columns: 1fr;
        align-items: center;
        gap: 2rem;
        padding: 1rem 1rem;
    }
```

### Continued development

I am still trying to figure out best practices of when to and when NOT to use utility classes.

## Author

- Github - [@ryanthayes](https://github.com/ryanthayes)
- Frontend Mentor - [@ryanthayes](https://www.frontendmentor.io/profile/ryanthayes)
