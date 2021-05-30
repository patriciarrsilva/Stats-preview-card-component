# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- View the optimal layout depending on their device's screen size

### Screenshots

![Mobile](./screenshots/mobile.png)
![Laptop](./screenshots/laptop.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/mobile-first-site-using-sass-and-bem-8l2AJmqX1)
- [Live Site URL](https://patriciarrsilva.github.io/Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- BEM

### What I learned

#### [Sass At-Rules (`@import` and `@use`)](https://sass-lang.com/documentation/at-rules/use#loading-members)

I learned that the Sass team will gradually phase out the `@import` rule over the next few years, and eventually remove it from the language entirely and that I should prefer the `@use` rule instead.

Because of this, I had to learn how to apply the `@use` rule (it uses namespaces).

#### [Link types: noopener - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/noopener)

I learned that the `noopener` keyword for the `rel` attribute of the `<a>` element instructs the browser to navigate to the target resource without granting the new browsing context access to the document that opened it.

This is especially useful when opening untrusted links, in order to ensure they cannot tamper with the originating document.

#### [Sass Basics](https://sass-lang.com/guide)

Once again, I had to search how to watch my source files for changes, and re-compile CSS each time I saved my Sass.

```
sass --watch scss/style.scss css/style.css
```

#### [Web fonts | MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts#using_an_online_font_service)

Once again, I had to search how to use Google Fonts in my project.

#### [picture - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)

I remembered that I can use the `<picture>` element to offer alternative versions of an image for different display scenarios.

### Useful resources

- [What is the difference between Normalize.css and Reset CSS?](https://stackoverflow.com/questions/6887336/what-is-the-difference-between-normalize-css-and-reset-css) - This discussion helped me finally understand the difference between Normalize and Reset CSS.
- [filter - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/filter) - This helped me to understand the different functions that can be used with the CSS filter property.
- [CSS object-fit property](https://www.w3schools.com/css/css3_object-fit.asp) - This helped me to understand how to make the image fit the available space even with screen resizing.

## Author

- GitHub - [Patrícia Silva](https://github.com/patriciarrsilva)
- Frontend Mentor - [@patriciarrsilva](https://www.frontendmentor.io/profile/patriciarrsilva)
- LinkedIn - [@patriciarrsilva](https://www.linkedin.com/in/patriciarrsilva/)
