# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./preview.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS transitions for hover effects

### What I learned

During this project, I learned how to create smooth hover transitions using CSS. Here's an example of the transition implementation:

```css
.social a {
  transition: all 0.3s ease;
}

.social a:hover {
  background-color: hsl(75, 94%, 57%);
  color: hsl(0, 0%, 8%);
}
```

This creates a smooth color transition when users hover over the social links, enhancing the user experience.

### Useful resources

- [CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/transition) - This helped me understand how to implement smooth hover effects.
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is an amazing article which helped me understand Flexbox layout.

## Author

- Frontend Mentor - [CherryRambler](https://www.frontendmentor.io/profile/CherryRambler)
- GitHub - [CherryRambler](https://github.com/CherryRambler)
