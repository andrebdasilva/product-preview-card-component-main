# Frontend Mentor - Product preview card component solution

<p align="left">
<a href="./docs/readme_pt-br.md">In portuguese</a>   
</p>

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop 1920px  
![](/screenshot/screenshot-desktop.png)

Mobile 375px  
![](/screenshot/screenshot-mobile.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS variables
- Responsive layout

### What I learned
I was able to put into practice the semantic HTML in the structure of the components.  
I reinforced the development of variables and media queries in CSS.  
I used tag picture to improve performance in responsiveness and take the media responsibility I wanted in CSS.    

```html
<picture>

  <source srcset="./images/image-product-desktop.jpg" media="(min-width: 768px)">

  <img src="./images/image-product-mobile.jpg" alt="perfume" class="product-image-mobile">

</picture>
```
## Author
- Frontend Mentor - [@andrebdasilva](https://www.frontendmentor.io/profile/andrebdasilva)

## Acknowledgments
- Thank you all from the Frontend Mentor
