# Frontend Mentor - Art gallery website solution

This is a solution to the [Art gallery website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each page depending on their device's screen size
- See hover states for all interactive elements throughout the site
- **Bonus**: Use [Leaflet JS](https://leafletjs.com/) to create an interactive location map with custom location pin

### Screenshot

![homepage](src/assets/screenshot-homepage.png)
![location page](src/assets/screenshot-location-page.png)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- CSS Grid
- Mobile-first workflow
- Leaflet JS
- React Leaflet
- [React](https://reactjs.org/) - JS library

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```js - I used the useNavigate hook to return a function that lets you navigate programmatically. Passing one value to another.
const navigate = useNavigate();

  const handleClickLocation = () => {
    navigate('/location')
    window.scrollTo(0, 0);
  }
```

### Continued development

- Amend the Leaflet Js Map to black and white, the map ive added does not match the styles of the design.
- Page is not responsive beyond 1549px.
- Add the footer as a reusable component - Did not do this due to the difference in color.
- Use styled components.

## Author

- Website - [Natasha Ramburrun](https://www.natasharamburrun.com)
- Frontend Mentor - [@natasharamburrun](https://www.frontendmentor.io/profile/natasharamburrun)
- Twitter - [@natasharamburrun](https://www.twitter.com/natasharamburru)
