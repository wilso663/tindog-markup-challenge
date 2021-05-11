# Frontend Mentor - Stats preview card component solution

This is a solution to the [TinDog Bootstrap exercise chapter by Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp). 

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

![Full Screen screenshot](./images/ScreenShot.png)


### Links

- Solution URL: [https://github.com/wilso663/stats-preview-card-component](https://github.com/wilso663/tindog-markup-challenge)
- Live Site URL: [https://musing-babbage-33fd3b.netlify.app/](https://musing-babbage-33fd3b.netlify.app/)

## My process

### Built with

- Bootstrap 4
- Desktop-first workflow

### What I learned

The most helpful thing that I learned was the ease of use of bootstrap grid layouts, particularly how to redefine it with utility classes:
```html
  <div class="col-12 col-md-6 col-lg-4 pricing-column">
```
```html   
  <div class="col-lg-6 col-12">
```
This made redefining the two required layouts very simple.

Learning to easily position photos behind other elements by specifying a z-index using
```css
  .img-rotate {
  position: absolute;
  }
  #features {
    z-index: 3;
  }
```
was also relatively simple.

### Continued development

My biggest issue in developing this was utilizing the grid system in combination with css grid to redfine the layout of sections. I would like to reposition the pricing elements based on the screen size by using something like grid-template-areas but combining this with bootstraps embedded grid system is something I haven't figured out how to do yet.

### Useful resources

- [Bootstrap Docs](https://getbootstrap.com/docs/4.3/examples/pricing/) - The official documentation for Bootstrap was fundamental in helping me understand how to begin utilizing utilty classes. It felt very intuitive to get a working layout with the bootstrap grid system by following the official documentation.
- [Font Awesome](https://fontawesome.com/icons/) - Font Awesome Icons are frequently used by websites made with bootstrap, so I decided to learn this as well and it is pretty easy to integrate with bootstrap styling since font awesome provides the markup elements.

## Author

- Website - [Stephen Wilson](https://github.com/wilso663)
- Frontend Mentor - [@wilso663](https://www.frontendmentor.io/profile/wilso663)


