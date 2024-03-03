
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Live Site URL: (https://mericadev.github.io/Frontend-Mentor-NFT-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript
- Flexbox
- Mobile-first workflow


### What I learned
I used z-index to overlay elemts on top of each other also used position types for positioning elements in relation to each other.

```css
nav ul {
    position: fixed;
    text-align: right;
   background-color: var(--white);
   border: 20x solid;
    z-index: 999;
    top: 0;
    right: 0;
    height: 100vh;
    padding: 2rem;
    margin-top: -2rem;
    width: 40%;
    transform: translateX(100%);
    transition: .2s ease-in-out;

    .circle-inner, .circle-outter {
    position: absolute;
    border-radius: 50%;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
  }

}
```

### Continued development

I aim to continue practicing my responsive design skills as well as mastering how to position elements with values like 'top' 'left' 'right' 'bottom'.

## Author

- Frontend Mentor - [@mericadev](https://www.frontendmentor.io/profile/mericadev)
- Twitter - [@merica_dev](https://www.twitter.com/merica_dev)


