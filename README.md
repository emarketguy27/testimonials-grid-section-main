<!-- @format -->

# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Learned a lot here about using CSS Grid layout.

Using grid-template-areas to manipulate element positioning and understanding the use of grid areas over css grid and the benefit to ease of understanding the layout.

To see how you can add code snippets, see below:

```css
article {
  display: grid;
  width: min(95%, 70rem);
  padding: 2em;
  margin-inline: auto;
  gap: 1.5rem;
  /* GRID TEMPLATE AREAS*/
  grid-template-areas:
    "one"
    "two"
    "three"
    "four"
    "five";

  .cards:nth-child(1) {
    grid-area: one;
  }
  .cards:nth-child(2) {
    grid-area: two;
  }
  .cards:nth-child(3) {
    grid-area: three;
  }
  .cards:nth-child(4) {
    grid-area: four;
  }
  .cards:nth-child(5) {
    grid-area: five;
  }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

## Author

- Website - [James Dennis](https://jamesdennis.org)
- Frontend Mentor - [@emarketguy27](https://www.frontendmentor.io/profile/James Dennis)

## Acknowledgments

Once again a tip of the hat to Kevin Powell for his excellent walkthrough explanation of CSS Grid
