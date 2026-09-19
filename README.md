# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Np6J7E5Bs). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Testimonials Grid Section](./preview.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/K0Teu4/TestimonialsGridSection)
- Live Site URL: [GitHub Pages](https://k0teu4.github.io/TestimonialsGridSection/)

## My process

### Built with

- Semantic HTML5 markup (article, header, blockquote, visually hidden h1)
- CSS Grid with grid-template-areas across three breakpoints
- Mobile-first workflow (1 column, then 2, then 4)
- CSS Custom Properties for the full palette
- Google Fonts (Barlow Semi Condensed, weights 500 and 600)

### What I learned

This challenge is the finale of the responsive layouts path: five cards, three very different layouts.

#### grid-template-areas as a layout language
Instead of placing each card with column and row numbers, I named the areas (daniel, jonathan, kira, jeanette, patrick) and redrew the whole layout per breakpoint by rewriting the areas map. The desktop map is two rows of four columns where Daniel spans two columns and Kira spans two rows; the tablet map is a two-column compromise; mobile is a plain stack. The card markup never changes.

#### Semantics of a testimonial
Each card is an article: a header with the avatar and the person's name, an h2 for the quote headline, and a blockquote wrapping the full review paragraph. The page title is a visually hidden h1 so the heading hierarchy stays correct without adding visual noise.

#### Contrast-driven color choices
On the purple and dark cards I picked the lightest palette values (purple-50, grey-100, grey-200) for secondary text so small labels like "Verified Graduate" still pass WCAG AA on colored backgrounds.

#### Decorative assets stay in CSS
The quotation mark SVG is a background-image on Daniel's card, layered with a subtle linear-gradient — decorative graphics belong in CSS, not in the HTML tree.

### Useful resources

- [MDN — grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
- [MDN — blockquote](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote)
- [web.dev — Color and contrast accessibility](https://web.dev/articles/color-and-contrast-accessibility)

## Author

- GitHub — [@K0Teu4](https://github.com/K0Teu4)
- Frontend Mentor — [@K0Teu4](https://www.frontendmentor.io/profile/K0Teu4)
