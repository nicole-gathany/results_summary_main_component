# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![](./assets/images/Screenshot%202023-11-03%20at%205.44.38 PM.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned how to use gradients and how to make circles using border-radius. I also practiced using display with flex and inline. 

I learned how to make web pages responsive to the size of the screen by using @media tags. 

To see how you can add code snippets, see below:

#### html
```html
   <h1 class="your-result">Your Result</h1>
        <div id="score-circle">
          <h2 class="total-score">76</h2>
          <h4 class="out-of-hundred">of 100</h4>
        </div>
        <h3 class="qualitative-comparison-title">Great</h3>
        <p class="qualitative-comparison">
          You scored higher than 65% of the people who have taken these tests.
        </p>
```
I'm proud of this html code not because it was technically difficult. I'm proud of thise code because I chose the h1, h2, h3, h4, and p tags not based on the default font size that these header and paragraph tags provide but rather based on the order of their importance on the webpage (i.e. h1 was the most important tag, h2 was the second most import and so on). This is important for accessibility standards and screen-readers. 


#### css

```css

  @media only screen and (max-width: 800px) {
  /* For mobile phones: */
  body {
    width: 375px;
  }
  .whole-component {
    display: flex;
    flex-direction: column;
  }
  .result {
    text-align: center;
    width: 375px;
    margin-left: -8px;
    padding-left: 37px;
    padding-right: 37px;
  }
  .qualitative-comparison {
    color: hsla(0, 0%, 100%, 0.475);
    inline-size: 200px;
    overflow-wrap: break-word;
    margin-left: 39px;
    margin-bottom: 32px;
    margin-top: -8px;
    
  }

  button {
    font-size: 20px;
  }
}

```

I'm proud of this css because this is the first time I'm using @media from scratch  or without legacy code that I could reference. I used the official MDN documentation for this (along with some Stack Overflow)

#### Javascript
```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```
I have not added js yet but I probably wil to get the json data.

### Continued development

I want to continue working on building responsive web applications and planning for responsiveness in the beginning. 

### Useful resources

- [Beginner's guide to media queries](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Media_queries) - This helped me to make the webpage responsive to mobile and desktop screens. I really liked this pattern and will use it going forward.
- [Flexbox Froggy](https://flexboxfroggy.com/) - I have to be honest and say that I didn't use official documentation for everything. I knew I wanted to use flexbox to get the symbol, the category names, the score, and the "/100" on the same line. I used Flexbox Froggy in the past so I thought it would be a good resource. 
**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Nicole Gathany](nicolegathany.com)
- Frontend Mentor - [@nicole-gathany](https://www.frontendmentor.io/profile/nicole-gathany)
- Twitter - [@\_goth_brooks](https://www.twitter.com/_goth_brooks)



## Acknowledgments

*Thank you to myself!! Thank you to myself, myself.*

I actually did not ask for community help on this. I almost did but I was a little bit stubborn in my approach maybe because I was shy or maybe because I really wanted to learn the content. 

I will say that I am very open to feedback especially on the responsiveness of this. I am not all that confident about the responsiveness of this webpage. 