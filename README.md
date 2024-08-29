# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
A simple blog card with a responsive title, mobile first. 
### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- Make it responsive between mobile and desktop

### Screenshot

![](./Screenshot%202024-08-29%20at%2008.56.57.png)

### Links

- [Solution URL here:](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS/hub)

-  [Live Site here:](fem-blog-post-main.netlify.app)

- [Check out my code on Github here:](https://github.com/Camperbug/fem-blog-post-main)

## My process
I started by making all my color variables and after that I put everything I needed on the HTML and finished with the CSS.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
I learned how to write a simple readme. my knowledge on flexbox got better. I learned how to do variables in CSS.

```html
    <div class="flex-avatar">
      <img src="./assests/userpic.jpg" alt="picture of greg">
      <p>
        Greg Hooper
      </p>
    </div>
```
```css
:root {
  /* primary colors */
  --clr-primary-1-yellow:
  hsla(47, 89%, 63%, 1);
  /* secondary colors */
  --clr-secondary-2-grey:
  hsla(0, 0%, 50%, 1);
  --clr-secondary-3-black:
  hsla(0, 0%, 7%, 1);
  --clr-secondary-4-white:
  hsla(0, 0%, 100%, 1);
  /* box shadow */
--shadow-1: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
--shadow-2: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
--shadow-3: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
--shadow-4: 0 20px 25px -5px rgb(0 0 0 / 0.1),
  0 8px 10px -6px rgb(0 0 0 / 0.1);
}
```

### Useful resources

- [udemy.com](udemy.com)  John Smilga; HTML&CSS Tutorial and Projects Course (Flexbox&Grid)-
This Udemy course helped me to learn the basics of HTML and CSS. Which was vital before going into this project.
- [Pixel to REM Converter](https://nekocalc.com/px-to-rem-converter) - 
This is a great resource and saves a lot of time in the long run.

## Author

- Frontend Mentor - [Daniel](https://www.frontendmentor.io/profile/Camperbug)