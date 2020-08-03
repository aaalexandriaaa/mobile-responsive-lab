<img src="https://i.imgur.com/qsSi07H.png">

# Flexbox / CSS Grid - Lab

## Intro

Time for some practice laying out elements using Flexbox and CSS Grid!

This lab is **a deliverable**.

## Lab

<img src="https://i.imgur.com/N4RdHqp.jpg">

- Use a combination of Flexbox and CSS Grid to layout the individual elements as close as possible - however, it does not have to be perfect! You are not being graded on matching fonts exactly or duplicating every glyph. The big idea here is CSS Grid/CSS Flexbox.

- Reproduce both the vertical and horizontal versions on the same page using responsive design!

## Set-Up

Create a project folder with `index.html` & `css/main.css` files. See today's lesson for step by step instructions.

## Hints

- Maybe use emojis in place of the stars/phone icon/message icon for simplicity. (IF you feel excessively bored, maybe use a free icon library like [font awesome](https://fontawesome.com) instead - Absolutely do not do this if you have not completed tic-tac-toe yet.)

- Elements can be made to appear circular by using `border-radius: 50%;`.

- Use any appropriate image you desire as the profile picture. Perhaps use [picsum.photos](https://picsum.photos) for a fast solution?

- You may want to start with a bit of CSS reset:

	```css
	html {
    box-sizing: border-box
  }
  
  /* The Universal Selector */
  *, /* All elements*/
  *::before, /* All ::before pseudo-elements */
  *::after { /* All ::after pseudo-elements */
    /* height & width will now include border & padding by default
       but can be over-ridden as needed */
    box-sizing: inherit;
  }
  
  /* resets font size to be 62.5% of the user preference - 
     in most browser configurations this will be 10px */
  :root {
    font-size: 62.5%
  }
  
  body {
    background-color: gray;
  /* Use a system font, if none are available use an available sans-sarif   font */
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
    margin: 0;
  }
	```
