# Frontend Mentor - Fylo data storage component solution

[![Netlify Status](https://api.netlify.com/api/v1/badges/391e4002-f54b-444d-b142-9563dcd7a62b/deploy-status)](https://app.netlify.com/sites/fylo-data-storage-component-solutions/deploys)  ![Github commit](https://img.shields.io/github/last-commit/Yashi-Singh-9/Fylo-Data-Storage-Component?label=last%20commit) 

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size.

### Screenshot

![Fylo Data Storage Component Screenshot](design/desktop-design.jpg)
![Fylo Data Storage Component Screenshot](design/mobile-design.jpg)

### Links

- [Solution](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n/hub?share=true)
- [Live Site](https://fylo-data-storage-component-solutions.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project, I focused on creating responsive designs using Flexbox and CSS Grid. I also experimented with CSS animations for the fade-in effects and smooth hover transitions. A notable challenge was ensuring the responsiveness of the progress bar and its dynamic elements like the data bubble, which was particularly tricky on larger screens.

Some code snippets I'm proud of:

```css
.progress-bar::before {
  background: linear-gradient(90deg, rgba(255, 163, 153, 1) 15%, rgba(255, 77, 151, 1) 100%);
  border-radius: 35px;
}
```

```html
<div class="data-bubble">
  <p class="data-bubble-text">
    <span>185</span> GB Left
  </p>
</div>
```

### Continued development

In future projects, I would like to focus more on:

- Optimizing animations for performance
- Exploring advanced CSS techniques for creating more complex UI components
- Working with more JavaScript to make the UI more interactive

### Useful resources

- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped me better understand Flexbox properties.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - General reference for HTML, CSS, and JavaScript.

## Author

- LinkedIn - [Yashi Singh](https://www.linkedin.com/in/yashi-singh-b4143a246)
- Frontend Mentor - [@Yashi-Singh-9](https://www.frontendmentor.io/profile/Yashi-Singh-9)

## Acknowledgments

Special thanks to [Frontend Mentor](https://www.frontendmentor.io) for providing such a great platform to improve coding skills. The challenge helped sharpen my CSS and responsive design knowledge.
