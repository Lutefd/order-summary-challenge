# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL:(https://www.frontendmentor.io/solutions/order-summary-using-css-flexbox-and-grid-HJXfRnAGq)
- Live Site URL:(https://ordersumchpj.netlify.app/)

## My process

This one took me a bit, I've just finished studying flexbox and grid so I wanted to apply both in a short project. I started by making the whole thing with grid, but it was always breaking in bigger screens and I wasn't able to quickly fix it with media queries, so i decided to make the container as a flexbox and some elements of it as a grid.After setting the container and styling the image and the title and info paragraph, I made the plans section as a three collum grid, styled it and then made another section for the buttons. The project was easy but I had to search for how to adjust and properly use some elements, so it wasn't the most speedy one.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned when to properly use grid and flexbox, the misuse of them in the beggining gave me quite a headache until I managed to understand how and when to use them

I loved being able to properly design the plans section visualing the grid lines with firefox dev tools

```html
<section class="plans">
  <div class="music-icon">
    <img src="/images/icon-music.svg" alt="" />
  </div>
  <div class="price">
    <strong>Annual Plan</strong>
    <span>$59.99/year</span>
  </div>
  <a href="#">Change</a>
</section>
```

I'm really happy i managed to style this

```css
.plans {
  display: grid;
  grid-template-columns: 0.8fr 1.2fr 1fr;
  justify-content: space-between;
  background: var(--secon-light);
  border-radius: 0.8rem;
  column-gap: 1rem;
  padding: 1rem;
  margin-left: 1rem;
  margin-right: 1rem;
}
.music-icon {
  justify-self: center;
  align-self: center;
}
.price {
  align-self: center;
  font-family: var(--ff-prim);
  font-size: 1rem;
  font-weight: 700;
  color: var(--secon-drk);
  font-size: 0.9rem;
}
.price span {
  color: var(--secon-a2);
  font-weight: 500;
  max-width: 800;
}
.plans a {
  align-self: center;
  margin-left: 2rem;
  color: var(--prim-2);
}
.plans a:hover {
  color: var(--prim-3);
  text-decoration: none;
}
```

### Continued development

I'm still not completely comfortable with using either flex or grid, but I'm feeling I'm starting to get the hang of it, so I really want to do more projects where I can learn further

## Author

- Frontend Mentor - [@Lutefd](https://www.frontendmentor.io/profile/Luistebaf)
- Twitter - [@luistebaf](https://www.twitter.com/Luistebaf)
- Linkedin - (https://www.linkedin.com/in/luis-dourado-09722a212/)
- Github - [@Lutefd](https://github.com/Lutefd)
