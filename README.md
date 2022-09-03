# Frontend Mentor | 3-column preview card component

This is a solution to the [3-column preview card component](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/screenshotMobile.png)

### Links

- Solution URL: (https://github.com/DorotaMroz/Frontend-Mentor-3-column-preview-card-component/edit/main/README.md)
- Live Site URL: (https://dorotamroz.github.io/Frontend-Mentor-3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

```css
/* Btn1 Styling */

button {
    background-color: var(--bright-orange);
    border: none;
    padding: .7rem 2rem;
    border-radius: 1rem;
    margin-left: 0;
    width: 140px;
    font-weight: 550;
    text-decoration: none;
    font-size: var(--font-size-p);
    background-color: var(--very-light-gray-background-headings-btn);
    transition-duration: 0.4s;
    border: 2px solid var(--very-light-gray-background-headings-btn);
}  

.button1 {
    background-color: var(--very-light-gray-background-headings-btn);
    color: var(--bright-orange);
 }

.button1:hover {
    background-color: var(--bright-orange);
    color: var(--very-light-gray-background-headings-btn);
    cursor: pointer;
 }
```
### Continued development

I'm still not completely comfortable with flexbox and grid techniques.

### Useful resources

- (https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_button_css)
This helped me with change the background color of a button with the background-color property. 
The button element - Styled with CSS.
- (https://nation.marketo.com/t5/knowledgebase/how-to-move-a-form-button-left-or-right-using-css/ta-p/248907)
How to move a form button left or right using CSS.

## Author

- Website - [Dorota Mroz]
- Frontend Mentor - [@DorotaMroz](https://www.frontendmentor.io/profile/DorotaMroz)
