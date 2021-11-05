## Welcome! 👋
## Table of contents
Pricing-component-with-toggle-master-main
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-View the optimal layout for the component depending on their device's screen size
-Control the toggle with both their mouse/trackpad and their keyboard
-Bonus: Complete the challenge with just HTML and CSS

### Screenshot

This is a screenshot of our solution.

![Alt-screen1](1_1.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript

### What We learned
We have learned how to use all these tools correctly. How to correctly prioritize when compiling a website. You can see important examples below.

Snippets:

html
            <div>
                <p>Annually</p>
                <label for="timeframe-toggle" class="timeframe-toggle" tabindex="0">
                    <input type="checkbox" id="timeframe-toggle">
                    <span class="slider"></span>
                </label>
                <p>Monthly</p>
            </div>

css
#timeframe-toggle:checked + .slider {
    background-color: Linear-Gradient(90deg, hsl(240, 75%, 85%), hsl(240, 65%, 65%));
}

#timeframe-toggle:checked + .slider:before {
    transform: translateX(1.5em);
}


```
## Author
Karina Kaukenova
- Github - [@kar11nko](https://github.com/kar11nko)
Yeskermes Aman
- Github - [@Yeskermes](https://github.com/Yeskermes)

## Acknowledgments

I want to thank Karina for his help. As they say, teamwork makes a dreamwork! We solved everything together
