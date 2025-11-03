# Frontend Mentor – Social Links Profile Solution  

This is my solution to the [**Social Links Profile challenge** on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

---

## Table of Contents  
- [Overview](#overview)  
  - [The Challenge](#the-challenge)  
  - [Links](#links)  
- [My Process](#my-process)  
  - [Built With](#built-with)  
  - [What I Learned](#what-i-learned)  
  - [Continued Development](#continued-development)  
  - [Useful Resources](#useful-resources)  
- [Author](#author)  

---

## Overview  

### The Challenge  
Users should be able to:  
- View the optimal layout depending on their device’s screen size  
- See hover and focus states for all interactive elements on the page  

---

### Links  

- **RepoGithub:** [Click here](https://github.com/Harmajabb/social-link-profile)  
- **Live Site URL:** [Click here](https://harmajabb.github.io/social-link-profile/)  

---

## My Process  

### Built With  
- Semantic **HTML5** markup  
- **CSS3 custom properties** (variables)  
- **Flexbox** and **CSS Grid** for layout  
- **Responsive design** using `min()`, `clamp()`, and media queries  
- **Mobile-first workflow**  
- **Accessibility features**: `:focus-visible`, `prefers-reduced-motion`  
- **Google Fonts – Inter**  

---

### What I Learned  

This challenge helped me practice modern CSS techniques and reinforce the idea of keeping a clean and scalable stylesheet structure.  
I focused on accessibility and responsiveness without using any framework.  

Here are some key CSS snippets I’m proud of:  


`/* Fluid and accessible typography */`
`:root {`
`  --fs-300: clamp(14px, 12px + .6vw, 16px);`
`  --fs-400: clamp(16px, 14px + .7vw, 20px);`
`  --fs-600: clamp(20px, 18px + 1vw, 28px);`
`}`

`/* Accessibility */`
`@media (prefers-reduced-motion: reduce){`
`  * { `
`    transition: none !important; `
`  }}`
`a:focus-visible {`
`  outline: 3px solid color-mix(in srgb, var(--green) 70%, white 30%);`
`outline-offset: 2px;`
`}`

### Continued Development

For future projects, I want to: 
- Integrate Sass nesting to structure my CSS more efficienty
- Add smooth transitions and light animations respecting accessibility preferences
- Experiment with component-based design using React for scability

### Useful Ressources

- [CSS Tricks – Fluid Typography with clamp()](https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/) – Excellent guide for creating fluid, responsive text sizing.
- [MDN – prefers-reduced-motion](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion) – Explained how to respect user motion preferences in my project. 
- [A11y Project – Focus States](https://www.a11yproject.com/posts/never-remove-css-outlines/) – Helped me design accessible focus states with `:focus-visible`.  
- [WebAIM Contrast Checker](https://userway.org/fr/verificateur-de-contraste/?fg=212424&bg=FFFFFF) – Useful for verifying color contrast accessibility on my dark background.  

### Author

- Lea Francois - Web development student at Wild Code School, currently learning fullstack development.
