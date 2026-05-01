# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/cideval-dev/qr-code-component.git)
- Live Site URL: [GitHub Pages](https://cideval-dev.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learned how to adapt a Figma draft into a website. The most difficult thing about this project was trying to adapt elements as 'hug' or 'fill' just like in Figma. I found this solution after looking for tips on the internet:

```css
display: flex;
width: min-content;
```

This code allows a container to adapt his width to the narrowest element (the QR code image in this situation).

### Continued development

Next I want to learn more about storing colors in variables, because for this first project I wanted to do things with simplicity. I also already experimented SCSS but I don't remember a lot. So I need to take another look on it.

I also have some difficulties to understand Flexbox correctly, especially for creating adaptive containers. I will exercise again on Flexbox Froggy.

### Useful resources

- [The famous Flexbox Froggy](https://flexboxfroggy.com/) - This website already helped me a few time ago to learn the principles of Flexbox.
- [MDN - drop-shadow()](https://developer.mozilla.org/fr/docs/Web/CSS/Reference/Values/filter-function/drop-shadow) - I looked on the internet about how to apply a drop shadow on an element.

### AI Collaboration

I used Gemini AI to get some help about adaptive elements because I couldn't find an effective solution on forums. Gemini couldn't understand me at first time but after giving more details and giving my code it helped me very well. Usually I use AI as another-hand solution. And I also don't copy code without understanding it properly.

## Author

- Website - [Vallérian Dicque](https://valleriandicque.myportfolio.com/projets-developpement)
- Frontend Mentor - [@cideval-dev](https://www.frontendmentor.io/profile/cideval-dev)
