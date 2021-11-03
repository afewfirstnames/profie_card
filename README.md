# Frontend Mentor - Profile card component solution

## Welcome! 👋

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![Project Screenshot](/images/screenshot.png)

### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [Live Site](https://jovial-neumann-bf9a95.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project was a challenge for me. It took me a while to figure out how to place the profile photo on top of the card header and body. Using a negative margin worked well in the end. I also struggled placing two background images in the appropriate place. I started by using pixel values until I realized I needed to use VH VW so the background can grow and shrink properly with the viewport. I attached that bit of CSS below!

```css
body {
  background-image: url("/images/bg-pattern-top.svg"),
    url("/images/bg-pattern-bottom.svg");
  background-position: right 50vw bottom 40vh, left 50vw top 50vh;
  background-repeat: no-repeat;
}
```

### Continued development

I'm looking forwared to keep refining my basic CSS skills and flexbox. I'm about to start learning CSS Grid.

## Author

- Frontend Mentor - [@afewfirstnames](https://www.frontendmentor.io/profile/afewfirstnames)
