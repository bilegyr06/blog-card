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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](blog-preview-card-main\Screenshot_12-12-2024_121319_127.0.0.1.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I went with the mobile-first approach. My first move was to create a <div> tag to contain
the whole blog card. Then I went on dividing and placing code or images into container <div> tags where necessary  

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

For some reason my <p> tag was not responding to any of the css I had attached to it.
I tried adding a class to it and calling it by that class, but even when I was using that class to address it there were no changes. That is until I used the css code below.

```css
p.maintxt{
    font-size: 16px;
    font-weight: 200;
}
```

## Author

- Frontend Mentor - [@bilegyr06](https://www.frontendmentor.io/profile/bilegyr06)
- linkedIn - [Ayodeji Ajayi](https://www.linkedin.com/in/ayodeji-ajayi-83006a287/)
