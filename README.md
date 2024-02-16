# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of project](./screenshot.jpg)

### Links

- Solution URL: [GitHub](https://your-solution-url.com)
- Live Site URL: [Live Site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Hover state

### What I learned

I tried to use a bit more semantic html on this project. Had to look up how to do the hover state to affect multiple elements when hovering over the whole <main> element, also working on transition to control the change in color of <h1> and the shadow placement was really cool!

```css
main:hover {
    cursor: pointer;

    h1 {
        color: var(--yellow);
    }

    box-shadow: 2rem 2rem;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Box-Shadows Properties](https://www.w3schools.com/cssref/css3_pr_box-shadow.php) - This helped me figure out how to properly set up the shadows, I wanted to get them as close as possible to the reference image but I had no idea how to control where it goes and how it looks.

## Author

- Website - [Fernando Batista](https://www.fernando-batista.webflow.io)
- Frontend Mentor - [@fernjbatista](https://www.frontendmentor.io/profile/fernjbatista)
