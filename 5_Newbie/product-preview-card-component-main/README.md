# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Technical Documentation](#technical-documentation)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/yourusername/product-preview-card)
- Live Site URL: [Live Demo](https://yourusername.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox for component layout
- CSS Grid for page centering
- Mobile-first workflow
- **CSS Nesting** for organized media queries
- **Art Direction** using the `<picture>` element

### What I learned

One of the highlights of this project was implementing **CSS Nesting**. It allowed me to keep my responsive logic right inside the component's block, making the code much easier to read and maintain.

I also focused on performance by using the `<picture>` element. Instead of downloading two images and hiding one with CSS, the browser now intelligently selects the correct asset based on the viewport width.

```html
<picture class="card-image">
  <source media="(min-width: 435px)" srcset="images/image-product-desktop.jpg">
  <img src="images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
</picture>
```

For the layout, I used a modern approach to center the card perfectly:

```css
body {
    display: grid;
    place-content: center;
    min-height: 100vh;
}
```

### Technical Documentation

I have created a dedicated, styled documentation page that goes deeper into my technical approach, design philosophy, and specific code implementations.

📖 **[View My Detailed Approach](./DOCUMENTATION.html)**

## Author

- Frontend Mentor - [@HavishyaVally](https://www.frontendmentor.io/profile/HavishyaVally)
- GitHub - [HavishyaVally](https://github.com/HavishyaVally)
