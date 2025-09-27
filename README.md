# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/product-preview-card-component-2Gy2YeMLUi)
- Live Site URL: [live site URL here](https://arturkobylianskyi.github.io/product-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

How to add icon to the button by css
```css
.button[data-icon="shopping-cart"]::before {
  content: "";
  background-image: url("images/icon-cart.svg");
  width: 15px;
  height: 16px;
}
```

How to use media 
```css
@media (min-width: 600px) {
  .product {
    grid-template-columns: 1fr  1fr;
  }
}
```

How to use picture 
```html
<picture class="product__img">
  <source media="(min-width: 600px)" srcset="images/image-product-desktop.jpg">
  <img class="main-image" src="images/image-product-mobile.jpg" alt="">
</picture>
```


### Useful resources

- [Best CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me for css reset.

## Author

- Website - [ArturKobylianskyi](https://github.com/Arturkobylianskyi)
- Frontend Mentor - [@Arturkobylianskyi](https://www.frontendmentor.io/profile/Arturkobylianskyi)
