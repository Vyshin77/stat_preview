# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

This challenge is to build out this card component and get it looking as close to the design as possible.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

The main thing I learned when working on this challenge revolves around how to get the image with the violet background together. This took a while for me to figure out but i was finally able to do it. I was able to do this by making the background-color of the section hsl(277, 64%, 61%), and then placing the image on its required position. 

Below are code snippets of my solution:
```css
  section {
  background-color: hsl(277, 64%, 61%);
  display: flex;
  align-items: stretch;
  justify-content: center;
  width: 70%;
  border-radius: 10px;
}

.images {
  width: 50%;
  /* background-color: hsl(277, 64%, 61%); */
  border-radius: 0 10px 10px 0;
}
```

## Author

- Frontend Mentor - [@Vyshin77](https://www.frontendmentor.io/profile/Vyshin77)
- Twitter - [@VyshinBrvh](https://www.twitter.com/VyshinBrvh)
