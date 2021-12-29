# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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
- See hover states for interactive elements

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Live Site URL: [Using github pages](https://noelroy.github.io/frontendmentor-challenges/nft-preview-card-component-main/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- rem unit : 1 rem unit = the font-size of the root component which is usually body tag.
- vh unit : represent 1% of the viewport height
- Using css variables
```css
:root {
  --bg-main: hsl(217, 54%, 11%);
}

body {
  background-color: var(--bg-main);
}
```
- Importing font and using it
```css
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap");
body {
  font-family: "Outfit", sans-serif;
  font-weight: 300;
}

```

### Continued development

- Learn to position images better
- Learn to use position absolute and relative together to display elements on top of each other
- Learn to centre objects both horizontally and vertically

### Useful resources

- [Image Overlay](https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me for displaying image overlay for the main image on hover.

## Author

- Frontend Mentor - [@noelroy](https://www.frontendmentor.io/profile/noelroy)
