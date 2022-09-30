# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge
- Adjusting the svgs 

Users should be able to:

- View the optimal layout for the section depending on their device's screen size


### Screenshot



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

I learned how to use svgs properly as a background
Using css grid properly
I also learnt the nth child pseudo class

```css
body{
    font-family: $font;
    justify-items: center;
    align-items: center;
    font-size: 15px;
    background: url("images/bg-pattern-top-desktop.svg"),url("images/bg-pattern-bottom-desktop.svg");
    background-color: $White;
    margin:0;
    background-repeat: no-repeat,no-repeat;
    background-position: left top, right bottom;
    min-height: 100vh;
    display: grid;
    grid-template-rows: [firsthalf-start]1.1fr [bottomhalf-start]0.9fr[bottomhalf-end];
    grid-template-columns: [lefthalf-start]1fr [righthalf-start]1fr[righthalf-end];
}

.review-content{
        margin-top: 2rem;
        padding: 0 2rem;
    }
    .review:nth-child(2){
        margin-top: 1rem;

    }
    .review:nth-child(3){
        margin-top: 2rem;

    }
```




### Continued development

Proper layouting , background properties

### Useful resources

- [Svg-as-background]https://github.com/MelvinAguilar/profile-card-component/blob/main/assets/css/style.css - This helped me to understand how svgs are used as background smartly. 
- [Nth-child-property]https://www.w3schools.com/cssref/sel_nth-child.asp - This helped me to know how to target the element based on the nth child number

## Author

- Website - [Sriram](https://www.your-site.com)
- Frontend Mentor - [sriramyrskprofessional](https://www.frontendmentor.io/profile/sriramyrskprofessional)

## Acknowledgments

@MelvinAguilar helped me with his code so thanks to him.