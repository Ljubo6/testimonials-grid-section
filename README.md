# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/Screenshot-testimonials-desktop.png)
![](./design/Screenshot-testimonials-mobile-top.png)
![](./design/Screenshot-testimonials-mobile-middle.png)
![](./design/Screenshot-testimonials-mobile-bottom.png)

### Links

- Solution URL: [https://github.com/Ljubo6/testimonials-grid-section]https://github.com/Ljubo6/testimonials-grid-section)
- Live Site URL: [https://ljubo6.github.io/testimonials-grid-section/](https://ljubo6.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
@media (min-width: 1200px){
  .cards{
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 282px 266px;
    column-gap: 30px;
    row-gap: 24px;
  }
  .card{
    width: 100%;
  }
  .one{
    background-position: 353px top;
    grid-column: 1 / 3;
    grid-row: 1;
  }
  .two{
    grid-column: 3 / 4;
    grid-row: 1;
  }
  .three{
    grid-column: 1 / 2;
    grid-row: 2;
  }
  .four{
    grid-column: 2 / 4;
    grid-row: 2;
  }
  .five{
    grid-column: 4 / 5;
    grid-row: 1 / 3;
  }
}
```
## Author

- Website - [https://github.com/Ljubo6/testimonials-grid-section](https://github.com/Ljubo6/testimonials-grid-section)
- Frontend Mentor - [@Ljubo6](https://www.frontendmentor.io/profile/@Ljubo6)
- Twitter - [@ljubo7788](https://www.twitter.com/@ljubo7788)
