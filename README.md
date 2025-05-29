# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Screenshot of the Blog preview card](./screenshot.png)

### Links

- Live Site URL: [Live Preview](https://rishabhsikka3.github.io/blog-preview-card/)
- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/responsive-blog-card-preview-using-css-flexbox-wojJx4ErQV)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- Responsive design using `max-width` and padding
- Custom font embedding with `@font-face`
- Hover states for interactivity

### What I learned

This project helped me practice layout centering using Flexbox instead of absolute positioning. I also learned:

- How to load and apply custom fonts using local `.ttf` files
- How to use CSS transitions for subtle hover effects
- Importance of using `max-width` with `width: 100%` to maintain responsiveness
- How to style elements using semantic class naming and structure

```css
.blog-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 24px;
}
```

### Continued development

In future projects, I want to:

- Explore using CSS `clamp()` for more fluid typography.
- Implement theme switching (light/dark) using CSS variables.
- Improve accessibility by ensuring keyboard navigation and screen reader compatibility.

### Useful resources

- [MDN Web Docs - @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)
- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_Concepts_of_Flexbox)
- [Frontend Mentor - Community Solutions](https://www.frontendmentor.io/solutions)

## Author

- Name – Rishabh Sikka
- Frontend Mentor – [@RishabhSikka3](https://www.frontendmentor.io/profile/RishabhSikka3)
