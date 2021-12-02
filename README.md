# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](assets/images/desktoppic.png)
![](assets/images/mobilepic.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/LeoSouzaNunes/stats-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://leosouzanunes.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I was able to apply a bit of CSS Grid for the first time and it was very useful to my desktop version setup. Down bellow i will be sharing a bit of my code with Grid.

```css
.card{
    display: grid;
    grid-template-columns: 51% 49%;
    grid-template-rows: 70%;
}
.image{
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
}
```

### Continued development

I intend to keep applying CSS Grid in my future projects and I would like to improve my code when it comes to responsivity and units, specially grid-template units. Finally I intend to apply SASS in my next frontendmentor project.

### Useful resources

- [MDN Web Docs - Basic Concepts of Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout) - Fundamental resource to learn some basics about CSS Grid.
- [W3schools - CSS Grid Layout](https://www.w3schools.com/css/css_grid.asp) - Also a very usefull article where i could learn some basics.

## Author

- Frontend Mentor - [@LeoSouzaNunes](https://www.frontendmentor.io/profile/LeoSouzaNunes)
