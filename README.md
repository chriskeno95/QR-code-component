# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned) 
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This README contains links to view my attempt at the QR component challege provided by Frontend Mentor. I was tasked with recreating the component so that it looked like the design brief.
 I have used what i have learned during my front end web development bootcamp course that i have recently started.
### Screenshot
![](../QR-code-component/images/my-QR-screenshot.png)


### Links

- Solution URL: [view repository URL](https://github.com/chriskeno95/QR-code-component)
- Live Site URL: [view here](https://chriskeno95.github.io/QR-code-component/)

## My process
I started with looking at the design brief and breaking it down into its visual elements by creating a mental wireframe.
 I created my html and added semantic HTML that I though best suited this project.
 I then opened css and started by creating css variables within the 'root'.
 ```css
:root {
    --background-colour: hsl(212, 45%, 89%);
    --cardcolour: hsl(0, 0%, 100%);
    --title:hsl(218, 44%, 22%);
    --text-colour:hsl(220, 15%, 55%);
}
```
 I only learned about these today so wanted to add them to this project to hold the style guide colours so that i could practice them in a real project.
 I then made my way through the other selectors to get positioning of the card and its content correct and as visually close as i could using CSS grid to center the QR component.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS variables


### What I learned
I learned how to view the project and break it down into manageable tasks. Firstly by getting a solid html foundation with semantic html and then building upon this in css by working my way down the elements bit by bit and putting in the basic styling of the tags.
 While completing this i learned abit more about parent/ child relationships and how to use 'width' more effectively as this had confused me slightly before as to when i was meant to use it, and what exactly it was to be used for.

## Author

- Frontend Mentor - [@chriskeno95](https://www.frontendmentor.io/profile/chriskeno95)
