# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [my-solution](#my-solution)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This is a challenge from the Frontend Mentor page.
In the ./design folder you can find the preview of the design for both mobile and desktop, for the 4-card feature section coding challenge.
### The challenge

- View the optimal layout for the site depending on their device's screen size.

### my-solution

![my-solution](./desktop-design-My-solution.jpg)

 
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

 Using media query and changing the areas you can modify an entire layout with just these grid-template-columns and grid-template-areas properties.
 We have created this layout (desktop view) in a desktop view and also in a mobile view.
 

```css
 @media (min-width: 768px){
    .card__container{
        grid-template-columns: repeat(3,1fr);
        grid-template-areas: 
        ".      card2       ."
        "card1  card2   card4"
        "card1  card3   card4"
        ".      card3       .";     
        gap: 2em;
    }
}
```
 
## Acknowledgments

Completion of the Modern CSS Master FlEXBOX and CSS GRID course from UDEMY

