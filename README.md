# Frontend Mentor - Results Summary Component Solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements (such as the Continue button)
- View color-coded skill category breakdowns with distinct background tints and icons

### Links

- **Live Site URL**: [Live Demo](https://mo-boop-ux.github.io/Result-Summary-Challenge/)
- **GitHub Repository**: [Result-Summary-Challenge](https://github.com/Mo-boop-ux/Result-Summary-Challenge)

---

## My Process

### Built With

- **Semantic HTML5** markup
- **CSS Grid & Flexbox** - Two-panel card layout on desktop, stacked layout on mobile
- **Google Fonts** - [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk)
- **CSS Gradients & Shadows** - Linear gradients for the score circle and result card background
- **Responsive Design** - Media queries for clean mobile presentation

### What I Learned

This project provided practice with subtle gradient styling and multi-part card structures:

1. **Vibrant Radial & Linear Gradients**:
   Creating depth using linear gradients on the primary result card:

```css
.result-card {
    text-align: center;
    padding: 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    background: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    border-radius: 20px;
}
```

2. **Categorized Summary Item Styling**:
   Giving each summary category a unique color badge with translucent background:

```css
.reaction { background: hsla(0, 100%, 67%, 0.05); color: hsl(0, 100%, 67%); }
.memory { background: hsla(39, 100%, 56%, 0.05); color: hsl(39, 100%, 56%); }
.verbal { background: hsla(166, 100%, 37%, 0.05); color: hsl(166, 100%, 37%); }
.visual { background: hsla(234, 85%, 45%, 0.05); color: hsl(234, 85%, 45%); }
```

### Useful Resources

- [Frontend Mentor](https://www.frontendmentor.io) - Real-world challenges for front-end practice.
- [MDN Web Docs - Using CSS gradients](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_images/Using_CSS_gradients)

---

## Author

- GitHub - [Mo-boop-ux](https://github.com/Mo-boop-ux)
- Frontend Mentor - [@Mo-boop-ux](https://www.frontendmentor.io/profile/Mo-boop-ux)
