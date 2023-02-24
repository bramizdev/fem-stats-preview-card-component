# Frontend Mentor - Stats preview card component solution

This is my solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Desktop
![Captura de pantalla 2023-02-23 a las 18 57 19](https://user-images.githubusercontent.com/112894363/221066019-977f95b0-0c93-47d6-99e8-0ac14d521c35.png)

- Mobile
![Captura de pantalla 2023-02-23 a las 18 57 12](https://user-images.githubusercontent.com/112894363/221066041-d7ed7aa0-351f-4f04-b3fa-da1d0d5b80dd.png)

### Links

- Solution URL: [https://github.com/bramizdev/fem-stats-preview-card-component](https://github.com/bramizdev/fem-stats-preview-card-component)
- Live Site URL: [https://bramizdev.github.io/fem-stats-preview-card-component/](https://bramizdev.github.io/fem-stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I practice how to create an overlay filter using a ```::before``` pseudo-element.

To see how you can add code snippets, see below:

```html
  <picture class="banner__picture">
    <source
      media="(min-width:768px)"
       srcset="./images/image-header-desktop.jpg"
    />
    <img
      class="banner__img"
      src="./images/image-header-mobile.jpg"
      alt="Three bussiness women having a bussiness meeting"
    />
  </picture>
```
```css
.banner__picture {
  position: relative;
}

.banner__picture::before {
  content: '';
  background-color: var(--clr-primary-500-t);
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  position: absolute;
}

```
## Author

- Website - [@bramizdev](https://github.com/bramizdev)
- Frontend Mentor - [@bramizdeve](https://www.frontendmentor.io/profile/bramizdev)
