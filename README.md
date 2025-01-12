# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/kabinny/FE_Mentor-BentoGrid](https://github.com/kabinny/FE_Mentor-BentoGrid)
- Live Site URL: [https://kabinny.github.io/FE_Mentor-BentoGrid/](https://kabinny.github.io/FE_Mentor-BentoGrid/)

## My process

### Built with

- CSS Grid
- Mobile-first workflow

### What I learned

Using the `grid-row` and `grid-column` properties with the 'span' value makes creating grid layouts easier. The first value indicates the starting number, while the second value indicates the ending number.

Instead of using the end number, using span along with the number of cells occupied is simpler to understand.

```css
.item01 { 
  grid-row: 1 / span 4; 
  grid-column: 2 / span 2;
}
```

### Useful resources

- [tailwindcss grid row](https://tailwindcss.com/docs/grid-row) - Tailwind CSS's grid system helped me define grid item areas. This intuitive system is easy to use in any context.

## Author

- GitHub - [@kabinny](https://github.com/kabinny)
- Frontend Mentor - [@kabinny](https://www.frontendmentor.io/profile/kabinny)

