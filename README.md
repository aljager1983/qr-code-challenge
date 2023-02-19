# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Links

- Solution URL: https://github.com/aljager1983/qr-code-challenge
- Live Site URL: https://aljager1983.github.io/qr-code-challenge/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned

Laying out the html is a bit easy. The styling part was less easy. At first I was hesitant to use CSS grid since I wasn't familiar with it. But it took me hours and still haven't got the result I wanted, so I crammed to study CSS grid and finally got the result I wanted. 

Below are the code snippets for the CSS grid:

```css for div element with className of container and content
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    text-align: center;
    height: 100vh;
}

.content {
    grid-column: 2/3;
    margin: auto;
    padding: 10px;
    max-width: 300px;
    background-color: white;
    border-radius: 20px;
}
```


### Continued development

I would still need to practice more on most aspects of CSS styling.

### Useful resources

- [The Net Ninja - Mobile-first build with CSS Grid](https://www.youtube.com/watch?v=PM3XW_1RAIs&list=PL4cUxeGkcC9hH1tAjyUPZPjbj-7s200a4) - This helped me for achieving responsiveness and mobile-ready pages. I really like his method of breaking down the topics.

## Author

- Frontend Mentor - [@aldrinbfernandez](https://www.frontendmentor.io/profile/aldrinbfernandez)
- Twitter - [@promdiGamer](https://twitter.com/promdiGamer)


## Acknowledgments

I have been a member of frontend mentor for a while, and I have seen your link in the discord of Angela Yu. I just recently finished her course of Web Development Bootcamp in Udemy. Thanks to her, I got the arsenal (tho still have a lot to learn) to accomplish this challenge.
