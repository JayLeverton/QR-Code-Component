# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author) 

## Overview

### Screenshot

![PC](screenshots/ScreenshotMobile.png)
![Tablets](screenshots/ScreenshotDesktop.png)

## My process

- I first wrote up a simple structure of the page in HTML. I began working with the mobile resolution first, using my phone to preview the site.
- After I was happy with the outline of the structure, I started with the broad strokes of the design, starting from the top-most containers and working my way down the page, using the specifications from the style guide for the colours and font.
- After getting the page looking somewhat similar to the design on mobile, I started refining the details, adjusting values and cleaning up my CSS somewhat as I went.
- When finished with the mobile preview, I started on the pc resolution which did not need much more work than a single media query to set the width of the card.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

As I'm still very new to HTML and CSS and this was my first time creating a page using a style guide, there were a few things that tripped me up. 
I ran into issues regarding the vertical centering of the card and, upon doing some trial and error and googling, learned that the way I was centering the card element using ```height: 100%;``` was the cause of the card refusing to be vertically centered. Replacing it with ```calc(100vh - 1px);``` fixed the issue. 
I'm still a little shakey on how to use all of the align and justify properties, but I'm getting the hang of them.

## Author

- [Website](https://www.your-site.com)
- [Frontend Mentor](https://www.frontendmentor.io/profile/JayLeverton)
- [LinkedIn](https://www.linkedin.com/in/jay-leverton-5079a7a4/)
- [Twitter](https://www.twitter.com/LevertonJay)