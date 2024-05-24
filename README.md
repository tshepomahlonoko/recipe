# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).  

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

## Overview

The challenge was to make a recipe page based on the style guide and the screenshots that were provided. I built my solution using HTML 5, CSS, GRID and Bootstrap. I also made use of Bootstrap 5 and a @media query to make the website mobile responsive. The guide was to make a mobile breakpoint at 375px however I set my mobile breakpoint at 480px because it makes the page friendlier to the eye.



### Screenshot

![Screenshot-mobile](./screenshots/Screenshot%202024-05-23%20at%2019-48-48%20Frontend%20Mentor%20Recipe%20page.png)
![Screenshot-desktop](./screenshots/Screenshot%202024-05-23%20at%2019-50-33%20Frontend%20Mentor%20Recipe%20page.png)


### Links

- Solution URL: [https://github.com/tshepomahlonoko/recipe](https://github.com/tshepomahlonoko/recipe)
- Live Site URL: [https://tshepomahlonoko.github.io/recipe/](https://tshepomahlonoko.github.io/recipe/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Bootstrap 5
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to manipulate tables using Bootstrap. I'm particularly proud of this code:

```css
tbody > tr:last-child > td  {
    border-bottom: 0;
}
```
This helped me remove the bottom border on the table which I found to be quite a challenge.  (see screenshot below).

![table-screenshot](./screenshots/Screenshot%202024-05-23%20at%2020-08-02%20Frontend%20Mentor%20Recipe%20page.png)

I also got stuck for a while when I got to the part where I was supposed to change the color of the text in the second column of the table. (see screenshot below). I'm particularly proud of this bit of code:

```css
#new-color td+td {
    font-weight: bold;
    color: hsl(14, 45%, 36%);    
}
```
![column-screenshot](./screenshots/Screenshot%202024-05-23%20at%2020-08-20%20Frontend%20Mentor%20Recipe%20page.png)


I also honed my skills on how to effectively use @media queries for responsiveness on my webpage.


### Continued development

Going forward I want to improve my ability to write lean code.

I also want to add Javascript to to my webpages to add functionality.

### Useful resources

- [Stack Overflow](https://www.stackoverflow.com) - Whenever I got struck this was a great resource. I learned a lot from the develper community at Stack Overflow
- [Bootstrap 5](https://www.getbootstrap.com/docs) - The documentation at Bootstrap helped a lot with being able to use it for responsiveness and good overall layout.

## Author

- Frontend Mentor - [@tshepomahlonoko](https://www.frontendmentor.io/profile/tshepomahlonoko)
- Twitter - [@tshepomahlonoko](https://www.x.com/tshepomahlonoko)


## Acknowledgments

Shoutout to the community at Stack Overflow. You guys have been a great help. Couldn't have done this without you. 

