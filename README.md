# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Frontend mentor solution](https://your-solution-url.comhttps://www.frontendmentor.io/solutions/responsive-landing-page-using-css-grid-EkH6LFWS0)
- Live Site URL: [My solution Live site](https://your-live-site-url.comhttps://yonosoysantiago.github.io/NFT-preview-card-component-challenge-hub/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge, I learned how to use CSS custom properties to create reusable styles. I also learned how to use CSS Grid to create a responsive layout.
One example of this is use the flex property to centralize content or the grid property to create a responsive layout.


```css
body{
    background-color: hsl(217, 54%, 11%);
    font-family: 'Outfit', sans-serif;
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
}

@media only screen and (min-width: 375px) {
    .card{
        width: 90%;
    }
}

@media only screen and (min-width: 720px) {
    .card{
        width: 20%;
    }
}

```

## Author

- Website - [Santiago Hurtado Solis](https://yonosoysantiago.github.io/)
- Frontend Mentor - [@YoNoSoySantiago](https://www.frontendmentor.io/profile/YoNoSoySantiago)


