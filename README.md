# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

- Desktop Screenshot:
![Desktop screenshot](./design/solution%20for%20desktop.png)
- Mobile Screenshot:
![Mobile screenshot](./design/solution%20for%20mobile.png)

### Links

- Solution URL: [Link for solution page](https://www.frontendmentor.io/solutions/chat-app-using-css-grid-with-bonus-initial-animation-on-page-load-4rfseBpkNn)
- Live Site URL: Link for live page](https://vignesh470.github.io/Chat-app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<p class="price">
            <input type="radio" id="price" name="price" value="30 minute walk $29">
            <label for="price">30 minute walk <span>$29</span></label><br>
          </p>
```

```css
@keyframes messages {
    0% {
        opacity: 0;
    }
    20% {
        opacity: 0;
    }
    40% {
        opacity: 0;
    }
    60% {
        opacity: 0;
    }
    70% {
        opacity: 25%;
    }
    75% {
        opacity: 35%;
    }
    80% {
        opacity: 50%;
    }
    90% {
        opacity: 75%;
    }
    100% {
        opacity: 100%;
    }
}
```

### Useful resources

- [Box-shadow](https://www.w3schools.com/cssref/css3_pr_box-shadow.php) - This helped me for setting good looking box shadow effects. I really liked this pattern and will use it going forward.
- [HTML Input Type=Radio](https://www.w3schools.com/tags/att_input_type_radio.asp) - This is an amazing article which helped me finally understand Input type=radio. I'd recommend it to anyone still learning this concept.
- [Custom radio button styling](https://reintech.io/blog/how-to-style-a-radio-button-with-css) - This article taught me to customize radio button style.

## Author

- Frontend Mentor - [@Vignesh470](https://www.frontendmentor.io/profile/Vignesh470)
- Twitter - [@vignesh470](https://www.twitter.com/vignesh470)
- LinkedIn - [Vignesh J](www.linkedin.com/in/vignesh-j-005a6291)
