# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](ScreenshotP.png)
![](ScreenshotP2.png)

### Links

- Solution URL: https://github.com/NamanG22/ProductCard
- Live Site URL: https://namang22.github.io/ProductCard/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Queries
- Mobile-first workflow

### What I learned

I was not able to find a way to change the image source of a particular image. So, I found out this way which is very simple and easy to implement.

```html
<img src="images\image-product-mobile.jpg" class="pImage" alt="...">
<img src="images\image-product-desktop.jpg" class="pImage2" alt="...">
```
```css
@media only screen and (min-width: 700px){
  .pImage{
    display: none;
  }
  .pImage2{
    display: inline;
  }
}
```

## Author

- Frontend Mentor - [@NamanG22](https://www.frontendmentor.io/profile/NamanG22)
