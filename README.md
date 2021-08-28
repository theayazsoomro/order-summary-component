# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![](./design/desktop-preview.jpg)
![](./design/mobile-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <title>Frontend Mentor | Order summary card</title>
    <link rel="stylesheet" href="stylesheet.css" />
  </head>
  <body>
    <div class="container">
      <div class="order-card">
        <img src="images/illustration-hero.svg" alt="illustration-hero" />

        <h2>Order Summary</h2>
        <p>
          You can now listen to millions of songs, audiobooks, and podcasts on
          any device anywhere you like!
        </p>
        <div class="price-component">
          <img src="images/icon-music.svg" alt="icon-music" />
          <div class="plan">
            <h3>Annual Plan</h3>
            <p>$59.99/year</p>
          </div>
          <a href="#">Change</a>
        </div>
        <div class="btn">Proceed to Payment</div>
        <a href="#" class="order-cancel">Cancel Order</a>
      </div>
      <div class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by <a href="#">Ayaz Soomro</a>.
      </div>
    </div>
  </body>
</html>
```
```css
@import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background-color: hsl(225, 100%, 94%);
  background-image: url(images/pattern-background-desktop.svg);
  background-repeat: no-repeat;
  width: 100%;
  height: 100vh;
  font-size: 16px;
}
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  text-align: center;
  width: 100%;
  height: 100vh;
}
.order-card {
  display: flex;
  align-items: center;
  flex-direction: column;
  width: 300px;
  height: auto;
  border-radius: 10px;
  background: #ffffff;
}
.order-card img {
  width: 100%;
  border-radius: 10px 10px 0 0;
  margin-bottom: 10px;
}
.order-card h2 {
  margin: 10px 0;
  color: hsl(223, 47%, 23%);
  font-family: "Red Hat Display", sans-serif;
}
.order-card p {
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.8rem;
  margin: 10px 0;
  opacity: 0.5;
}
.order-card .price-component {
  display: flex;
  align-items: center;
  margin: 20px 0;
  width: 250px;
  height: 60px;
  border-radius: 5px;
  background: hsl(225, 100%, 98%);
}
.order-card .price-component img {
  display: inline-block;
  width: 34px;
  height: 34px;
  margin: 10px 10px;
}
.order-card .price-component .plan h3 {
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.8rem;
  margin: 5px 0;
}
.order-card .price-component .plan p {
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.8rem;
  opacity: 0.5;
  margin: 0;
}
.order-card .price-component a {
  display: block;
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.7rem;
  margin-left: 60px;
}
.order-card .price-component a:hover {
  text-decoration: none;
  color: hsl(228, 45%, 44%);
}

.order-card .btn {
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.7rem;
  width: 250px;
  padding: 10px 30px;
  margin: 10px 0 30px 0;
  color: #ffffff;
  border-radius: 5px;
  background: hsl(245, 75%, 52%);
  box-shadow: 0 10px 30px hsl(228, 45%, 44%);
}
.order-card .btn:hover {
  cursor: pointer;
  background: hsl(228, 45%, 44%);
}

.order-cancel {
  font-family: "Red Hat Display", sans-serif;
  font-size: 0.7rem;
  text-decoration: none;
  margin-bottom: 20px;
  font-weight: 700;
  color: hsl(228, 45%, 44%);
}
.order-cancel:hover {
  color: hsl(223, 47%, 23%);
}
/* Footer Component */
.attribution {
  position: relative;
  top: 20px;
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}

/* Break-Point at max-width 375px */
@media screen and (max-width: 375px) {
  .container {
    width: 100%;
    height: 100%;
  }
}
```

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@Ayaz Soomro](https://www.frontendmentor.io/profile/theayazsoomro)
- Twitter - [@Ayaz Soomro](https://www.twitter.com/theayazsoomro)
