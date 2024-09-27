# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Deploy Status](#deploy-status)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](https://github.com/TusharKaundal/QR_code/blob/0d641b86c26592d616bba75c7595fbd7da3eb79e/images/screenshot-desktop.png)

### Links

- Solution URL: [Github](https://github.com/TusharKaundal/QR_code) 🎉🎉
- Live Site URL: [NetLify](https://stately-cobbler-a2ea46.netlify.app/) 🎊🎊

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Learned how to adjust footer to bottom while being the display property being defined as flex.
- Learned how to use Figma and using figma design to convert it into design using CSS

```css
body {
    background-color: hsl(212, 45%, 89%);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 100vw;
    height: 100vh;
}
footer {
    position: absolute;
    bottom: 5px;
}
```

- Will try to get better solution for similiar cases with good solution.

### Useful resources

- [Resource 1](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me in card creation using CSS - Flexbox.
- [Resource 2](https://medium.com/frontend-mentor/frontend-mentor-trusted-hosting-providers-bf000dfebe) - This is an amazing article which helped me in recommendation for hosting website.

## Author

- Website - [Tushar Kaundal](https://stately-cobbler-a2ea46.netlify.app/)
- Frontend Mentor - [@TusharKaundal](https://www.frontendmentor.io/profile/TusharKaundal)

## Deploy Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/27f8b909-3a7a-4536-b5dc-f53d2b55c58a/deploy-status)](https://app.netlify.com/sites/stately-cobbler-a2ea46/deploys)
