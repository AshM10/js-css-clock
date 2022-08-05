# js-css-clock

This is a solution to the [JA and CSS Clock on #JavaScript30](https://javascript30.com). 30 day vanilla JS coding challenge.

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

### The challenge

Users should be able to:

- See exact hour, minutes and seconds.

### Screenshot

<img width="1433" alt="Screen Shot 2022-08-04 at 10 45 26 AM" src="https://user-images.githubusercontent.com/89284873/182893290-950c1b6e-f887-4ed2-a068-8eee7c3b229c.png">

### Links

- Solution URL: [GitHub](https://github.com/AshM10/js-css-clock)
- Live Site URL: [Netlify](https://ash-js-css-clock.netlify.app)

## My process

### Built with

- CSS transform properties
- Vanilla JavaScript

### What I learned

- CSS transition-timing-function

To see how you can add code snippets, see below:

```css
transform-origin: 100%; /* Moved the hand to a different position */
transform: rotate(90deg); /* makes the hand rotate */
transition: all 0.05s;
transition-timing-function: cubic-bezier(
  0.1,
  2.7,
  0.58,
  1
); /* this would be the transition effect of the hand */
```

### Continued development

Continue with Challenge #2.

## Author

- Website - [Ash Moreno](https://www.ashmoreno.dev)
- Twitter - [@sexy_gravy](https://twitter.com/sexy_gravy)
