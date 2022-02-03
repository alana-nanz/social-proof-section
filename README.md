# Frontend Mentor - Social proof section

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Created a responsive design using mobile first approach.

### Screenshot

design/screenshot.jpg

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-social-proof-section-F7PoHdEXN
- Live Site URL: https://alana-nanz.github.io/social-proof-section/

## My process

- After downloading the starter code and setting up my files, I started by writing the html. 
- After finishing the html, I wrote CSS for the mobile design and then CSS for the desktop design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I needed use a combination of classes and ids for the desktop design:
```html
<div class="rating" id="top"></div>
```

- You can add two background images and specify placement:
```css
body {
  background-image: url('../img/bg-pattern-top-mobile.svg'), url('../img/bg-pattern-bottom-mobile.svg');
  background-repeat: no-repeat;
  background-position: top left, bottom right;
}
```

-To make a square image a circle, I added a border-radius of 50%:
```css
.headshot {
  border-radius: 50%;
}
```

### Continued development

- I plan to continue learning about flexbox properties. 
- I want to better understand when to use flexbox on containers and/or their contents.
- I want to better understand when to use fixed widths vs. percentages.

### Useful resources

- https://www.w3schools.com/howto/howto_css_rounded_images.asp - This helped me learn about creating a cirular image.

## Author

- Website - https://www.alanananz.com
- Frontend Mentor - [@alana-nanz] https://www.frontendmentor.io/profile/alana-nanz
- Github - [@alana-nanz]https://github.com/alana-nanz