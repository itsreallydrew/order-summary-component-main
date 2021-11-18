# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This was my first coding challenge in following a mockup from scratch. I decided to use CSS grid as my main tool for creating this design.

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screenshot 2021-11-18 at 05-40-29 Frontend Mentor Order summary card](https://user-images.githubusercontent.com/88289750/142409042-852122de-5501-4a15-ab7a-c2629c6f9d3d.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj/hub/responsive-order-summary-card-using-css-grid-zG7qSoOhW)
- Live Site URL: [Live Site](https://thirsty-shannon-ee26e7.netlify.app/)

## My process

I started out by laying out the page with 8 grids and rows. I then chose what part would be taken up by the background pattern and then began to add the card. I decided to set the pattern section to flex since I was unsure of how to center it with grid. That was the most challenging part.

I am most proud of the fact that I built the entire card using grid. Normally that would be a challenge for me because I would be set on trying to decide on a specific height. I have learned that with using grid it will adjust to the height of the content.

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

It seems simple but this is how I defined the size of the card:

```css
display: grid;
grid-template-rows: repeat(5, min-content);
gap: 3rem;
```

### Continued development

I want to continue to work with CSS grid. I like the fact that grid tends to be more inherently responsive than flexbox and requires less code and media queries. I am still learning to properly use the minmax function which is a big help when it comes to responsiveness. I feel like I have improved when it comes to writing semantic HTML but I also need to make sure I include proper labels for accessibility.

## Author

- Frontend Mentor - [@itsreallydrew](https://www.frontendmentor.io/profile/itsreallydrew)

## Acknowledgments

A lot of my recent experience with CSS grid came from following a Udemy tutorial found here (https://www.udemy.com/course/advanced-css-and-sass/)
