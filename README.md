# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- bootstrap

### What I learned

` Hi everybody, welcome to my new solution :blush:
At first look this project seemed to be easy but positioning the background bubbles responsively turned out to become a real chalenge.

Thanks to [APG solution on Frontend Mentor](https://www.frontendmentor.io/solutions/card-component-with-3d-animation-t0NqrfqMT#comment-630cd1723fba76c6d9add1d8) that helped me with background bubbles, it was a briliant idea to combine vw & vh to position the background vertically.:boom:
In this project i read some more in depth about background and learned alot, espacialy about background position.

I thought it would be a good idea to chang the size of bubbles when the size of viewport changed.
So I used a variable amount(vmax) and add some fixed amount (px) to it, because i didnt want background to become so small or disapear when the vp is so small.
I used grid for implementing the card part which was enjoyable and so helpful.
in the code below you can see the part of code I used for background part.
If you have any idea to improve my code or design it would be precious to me ,so plz let me know`

```css
body {
  background: url(../images/bg-pattern-top.svg),
    url(../images/bg-pattern-bottom.svg), var(--sm-bg-color);
  background-repeat: no-repeat;
  background-size: calc(70vmax + 100px);
  background-position: right calc(47vw + 15%) bottom calc(65vh - 15vw), left
      calc(40vw + 25%) top calc(72vh - 10vw);
}
```

### Useful resources

- [resource 1](https://dev.to/this-is-learning/all-you-need-to-know-about-background-position-3aac) - This helped me learn more in depth about background position.

## Author

- Frontend Mentor - [@somaye-beiranvand](https://www.frontendmentor.io/profile/somaye-beiranvand)
