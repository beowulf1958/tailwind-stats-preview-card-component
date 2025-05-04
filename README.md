# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenschot](./images/Screenshot%202025-05-04%20%20Frontend%20Mentor%20Stats%20preview%20card%20component.png)


### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/stats-preview-using-tailwind-css-MJRRQEd7XW)
- Live Site URL: [Live site URL here](https://tailwind-stats-preview.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- [Tailwind](https://reactjs.org/) - Tailwind CSS framework


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Continuing the tailwind CSS journey, this is a re-do of the challenge using tailwind. I was able to use the <picture> tag to swap out the pictures, although in this challenge it is hard to tell because the two pictures are so very similar.


```css
.hero::before {
    content: " ";
    width: 100%; 
    height: 100%; 
    opacity: 20%;
    background-color: #f019f4; 
    position: absolute;
    top: 0;
    left: 0;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**


## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)


## Acknowledgments

[@Opeyemi-stack](https://www.frontendmentor.io/solutions/responsive-nft-preview-card-component-1pOqSIIJbD ) helped me with the overlay element from the nft preview card challenge. That project showed me how to use ::before with an img element to produce a colored overlay.

[@KKen007](https://www.frontendmentor.io/solutions/stats-preview-card-component-main-kbdnWmk9G8) also has a great solution to this challenge which influenced me.


