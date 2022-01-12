# Frontend Mentor - NFT preview card component solution


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
-This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge
-- Build it to look as close as possible to the design provided.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop-preview](https://user-images.githubusercontent.com/49578782/149049641-d72fcc1b-4734-41df-8735-29199d0dbcd8.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- 

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned
- How to use opacity to make element invisible and then visible with hover 


```css
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  background-color: rgb(0, 255, 247, 0.4);
  width: 100%;
  height: 100%;
  opacity: 0;
  transition: all 300ms ease-out;
}

.overlay:hover,
.overlay:active {
  opacity: 1;
  cursor: pointer;
}
```

### Useful resources

- [MDN] https://developer.mozilla.org/en-US/ - Read up about box-shadow as a reminder
- https://stackoverflow.com - checked out answers about the different ways to make an element invisible 


## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_Black84](https://www.twitter.com/D_Black84)

