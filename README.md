# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
```html
 <main class="container">
    <section class="card_sedans">
      <img src="./images/icon-sedans.svg" alt="icono">
      <h2 class="card_title">Sedans</h2>
      <p class="card_texto">Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city 
          or on your next road trip.</p>
      <button class="card_btn btn_sedans">Learn More</button>
    </section>

    <section class="card_suvs">
      <img src="./images/icon-suvs.svg" alt="iconi">
      <h2 class="card_title">SUVS</h2>
      <p class="card_texto">Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation 
        and off-road adventures.</p>
      <button class="card_btn btn_suvs">Learn More</button>
    </section>

    <section class="card_luxury">
      <img src="./images/icon-luxury.svg" alt="icono">
      <h2 class="card_title">Luxury</h2>
      <p class="card_texto">Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury 
          rental and arrive in style.</p>
      <button class="card_btn btn_luxury">Learn More</button>
    </section>
  </main>
```

```css
.container{
    display: flex;
    height: 380px;
    background-color: antiquewhite;
    border-radius: 10px;
    overflow: hidden;
}
section{
    padding: 40px;
}
.card_sedans{
    background-color: var(--Bright-orange);
}
.card_suvs{
    background-color: var(--Dark-cyan);
}
.card_luxury{
    background-color: var(--Very-dark-cyan);
}
.card_title{
    margin: 10px 0;
    font-size: 25px;
    font-family: 'Big Shoulders Display', cursive;
    text-transform: uppercase;
    color: var(--Very-light-gray);
}
.card_texto{
    font-size: 11px;
    font-weight: 100;
    vertical-align: 3px;
    margin-top: 20px;
    font-family: 'Lexend Deca', sans-serif;
    color: var(--Very-light-gray);
}
.card_btn{
    width: 100px;
    height: 30px;
    border: none;
    border-radius: 50px;
    margin-top: 40px;
    font-family: 'Lexend Deca', sans-serif;
}
.btn_sedans{
    color: var(--Bright-orange);
}
.btn_suvs{
    color: var(--Dark-cyan) ;
}
.btn_luxury{
    color: var(--Very-dark-cyan);
}
.card_btn:hover{
    background-color: transparent;
    border: 1px solid var(--Very-light-gray);
    color: var(--Very-light-gray);
}: papayawhip;
}
```
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned


and streamlined the use of technologies to perform the layout

### Continued development

Three sessions were created in which each of the cards was made with the required design and effects. In the CSS part, variables were used to make the design more efficient.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author
- Rosalba Galicia Ramos
- Frontend Mentor - [@RosaGR01](https://www.frontendmentor.io/profile/RosaGR01)



## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
