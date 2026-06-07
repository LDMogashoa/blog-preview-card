# Frontend Mentor - Blog preview card solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Blog Preview Card Screenshot](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/LDMogashoa/blog-preview-card)
- Live Site URL: [Live Site](https://LDMogashoa.github.io/blog-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- Mobile-first workflow
- Figtree variable font
- CSS animations and transitions

### What I learned

Working on this project helped me understand how to use CSS custom properties to manage design tokens like colours and font weights in one place. I also got better at using flexbox to centre content both vertically and horizontally on the page.

One thing I am proud of is the hover effect on the card. I used CSS transitions to make the card lift up smoothly when you hover over it and the title changes colour:

```css
.card:hover {
  transform: translate(-4px, -4px);
  box-shadow: 12px 12px 0px var(--gray-950);
}

.card:hover .card__title {
  color: var(--yellow);
}
```

I also learned how to load custom fonts using @font-face which made the design look exactly like the original:

```css
@font-face {
  font-family: 'Figtree';
  src: url('./assets/fonts/Figtree-VariableFont_wght.ttf') format('truetype');
  font-weight: 100 900;
}
```

### Continued development

In future projects I want to get better at:

- Writing more advanced CSS animations
- Building more complex layouts using CSS Grid
- Making websites fully accessible with proper ARIA attributes
- Learning JavaScript to make cards interactive and dynamic

## Author

- Name - Lethabo David Mogashoa
- Frontend Mentor - [@LDMogashoa](https://www.frontendmentor.io/profile/LDMogashoa)
- GitHub - [@LDMogashoa](https://github.com/LDMogashoa)
- Email - lethabodavid60@gmail.com
