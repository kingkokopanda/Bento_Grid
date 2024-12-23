# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Creating my first bento grid using CSS and HTML was an exciting and insightful journey into front-end development. This project taught me new skills and deepened my understanding of layout systems, responsive design, and aesthetic adjustments. Here’s an overview of what I learned:
### The challenge

- View the optimal layout for the interface depending on users device's screen size

### Screenshot

![bento screenshot](https://github.com/user-attachments/assets/81f285c1-056c-42c3-9a8d-0c8696b7c6dd)

### Links

- Solution URL: [kingkokopanda/Bento_Grid](https://github.com/kingkokopanda/Bento_Grid)
- Live Site URL: [Bento Grid](https://kingkokopanda.github.io/Bento_Grid/)

## My process
This was my first time using the CSS Grid layout, and it proved to be a powerful tool for creating structured, modular designs.
I learned how grid tracks, gaps, and alignment properties come together to create a cohesive layout.
Understanding the flexibility of grid-template-areas and grid-template-columns/rows allowed me to experiment and achieve the desired bento-box effect.

-Previous Knowledge of rem Units Paid Off
Having used rem for scaling in previous projects gave me a solid foundation for consistent spacing and typography in this project.
I realized how beneficial rem is for responsive design, especially when paired with grid layouts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

-Leveraging Utopia for Measurements
Despite my familiarity with rem, I used Utopia to refine my measurements and maintain harmony across different screen sizes.
This tool helped me create a balance between fixed and fluid dimensions, ensuring a visually appealing and scalable design.

```css
.tile-1__header{
    text-align: center;
    font-size: clamp(2.9rem, 3rem, 4rem);
    font-weight: 500;
    margin: 2.4rem;
    line-height: 92%;
}

.tile-1__header > mark{
    color: var(--Yellow-500);
    background-color: transparent;
}

.tile-1__image{
    display: block;
    margin:-1rem auto;
    width: 55%;
}
```

### Continued development

I want to explore more creative ways to make my mobile layouts visually “cooler” while maintaining usability.
Ideas like incorporating animations, hover effects, or dynamic content changes could bring more life to the design

### Useful resources

- [Clamp measurements](https://utopia.fyi/clamp/calculator/?a=320,1240) - This helped me calculate the proper clamp sized when styling my grid. I really liked this pattern and will use it going forward.

## Author

- Website - [Kingkokopanda](https://github.com/kingkokopanda)
- Frontend Mentor - [@Kingkokopanda](https://www.frontendmentor.io/profile/kingkokopanda)


## Acknowledgments

To myself:  This project marked a significant step in my front-end development journey. It not only strengthened my technical skills but also sparked a desire to push creative boundaries in future projects. Feedback and guidance would be greatly appreciated as I work toward refining and enhancing my bento grid designs!
