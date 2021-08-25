# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the ![Fylo dark theme landing page challenge on Frontend Mentor](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Fylo-dark-theme-landing-page-solution.github.io)

- [Live Site URL](https://tmraz.github.io/Fylo-dark-theme-landing-page-solution.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](./css/main.css) - For Desktop style
- [Styled Components](./css/mobile.css) - For Mobile style

### What I learned

Snippets, see below:

Email input:

```html
<form action="#" method="get">
  <input type="email" name="email" placeholder="example@example.com" class="required" required>
                        
  <button>
     Get Started For Free
  </button>
</form>

```

Change of the placeholder color:

```css
::-webkit-input-placeholder { /* Chrome/Opera/Safari */
    color: #ccc;
}

```

Linear gradient at angle:

```css
--color-bg-gradient: linear-gradient(160deg, hsl(176, 68%, 64%), hsl(198, 60%, 50%));

```

### Useful resources

- [Change of the svg color](https://css-tricks.com/almanac/selectors/p/placeholder/) 
