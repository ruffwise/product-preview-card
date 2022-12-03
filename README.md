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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./product-preview-card-component-main/images/Screenshot 2022-09-24 at 16-26-38.png)

### Links

- Solution URL: [https://github.com/ruffwise/product-preview-card](https://github.com/ruffwise/product-preview-card)
- Live Site URL: [https://ruffwise.github.io/product-preview-card/](https://ruffwise.github.io/product-preview-card/)

## My process

1. I added background color to the body of the page
2. I created a div with class of "div-product" to serve as parent div. I then created two seperate div (div-image) and (div-description) to serve as place holder for the product image and the text (description)
3. For desktop view, I used display: flex to align the divs in a row
4. I used external CSS for the styling of this challange

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

1. I learnt how to use the picture element to display different pictures based on screen size

```html
<picture>
  <source
    media="(min-width: 376px)"
    srcset="images/image-product-desktop.jpg"
    alt="desktop-image"
  />
  <img
    class="picture"
    src="images/image-product-mobile.jpg"
    alt="mobile-image"
  />
</picture>
```

2. I learnt how to use the media query to change css styling based on screen size

```css
@media (min-width: 376px) {
  .div-product {
    display: flex;
    width: 38rem;
    margin: 10rem auto;
  }
}
```

### Continued development

I am beginner, I started learning HTML/CSS some months ago, I am following a tutorial course on Udemy. The tutorial led me to frontendmentor.io and I decided to try my hands on the challenges for newbies. I am still learning and will love every guidance I can get

### Useful resources

- [resource 1](https://webdesign.tutsplus.com/tutorials/quick-tip-how-to-use-html5-picture-for-responsive-images--cms-21015) - This helped with understanding how to use the picture element to display different picture.
- [resource 2](https://www.youtube.com/watch?v=nHB-3WJTfSg) - This video helped me to better understand how to use the picture element.

## Author

- Frontend Mentor - [@ruffwise](https://www.frontendmentor.io/profile/ruffwise)
