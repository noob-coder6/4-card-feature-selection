# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [GitHub Repository](https://github.com/noob-coder6/four-card-feature-section)
- Live Site URL: [Live Demo](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- BEM naming convention
- Google Fonts (Poppins)

### What I learned

This project helped me strengthen my understanding of CSS Grid, particularly in creating complex layouts with precise positioning. I learned how to effectively use grid-template-columns, grid-template-rows, and grid placement properties to create a diamond-shaped card layout on desktop while maintaining a simple stacked layout on mobile.

Key learnings include:

**CSS Grid for centering content:**
```css
body {
  display: grid;
  place-content: center;
  min-height: 100vh;
}
```

**Creating a responsive grid layout:**
```css
.cards-container {
  display: grid;
  gap: 1.5rem;
}

@media (min-width: 1100px) {
  .cards-container {
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, auto);
  }
}
```

**Precise card positioning with grid lines:**
```css
.card--cyan {
  grid-column: 1 / 2;
  grid-row: 1 / 3;
  align-self: center;
}
```

I also improved my understanding of CSS custom properties for maintaining consistent design tokens and the BEM methodology for organized, scalable CSS architecture.

### Continued development

In future projects, I want to continue focusing on:

- Advanced CSS Grid techniques and exploring CSS Subgrid
- Improving accessibility with proper ARIA labels and semantic HTML
- Implementing smooth animations and transitions for enhanced user experience
- Exploring CSS container queries for more responsive component design
- Practicing more complex grid layouts and mastering grid-template-areas

## Author

- GitHub - [@noob-coder6](https://github.com/noob-coder6)
- Frontend Mentor - [@noob-coder6](https://www.frontendmentor.io/profile/noob-coder6)