# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles



### What I learned

I have learned how to use css methodologies.
I have learned how to be creative and confident.
I have also learned how to make an image align with a text
```html
       <p class="bottom-items"><img src="Image/image-avatar.png" alt="Avatar" align="center" width="48px" height="48px">   <em class="bottom-text last-word"><span id="creat">Creation of</span> <span  class="jules wyvern">Jules Wyvern</span></em></p>
  ```
  ```css
  .bottom img{
  border-radius:50px; 
  border:3px solid hsl(0, 0%, 100%);
  margin-right:30px
  }
  ```
  I have learned how to overlay text and color on an image.
  ```html
      <div class="Equilibrium-img" id="image">
        <img src="Image/image-equilibrium.jpg" alt="Equilibrium image" width="500px" height="500px"/>
      </div>
  ```
  ```css
  .Equilibrium-img:hover {
    
    top:50%;
    left:50%;
    background:url(Image/icon-view.svg) center  no-repeat;
      background-color:hsl(178, 100%, 50%);
     background-size:100px;
  
  }
  
  .Equilibrium-img img:hover {
    cursor:pointer;
    overflow: hidden;
    color:hsl(178, 100%, 50%);
    object-fit: cover;
  transition:0.3s;
    opacity:.3;
  
  }
```


### Continued development


Flexbox.
Css Gradient.
Css Methodologies and Architectures.
Mobile First workflow.
Javascript.



### Useful resources


-Learn HTML and CSS with w3schools by Hege Refsnes, Ståle Refsnes, Kai Jim Refsnes, Jan Egil Refsnes with C. Michael Woodward.- This is an amazing book which helped me finally understand Html and Css. I'd recommend it to anyone still learning this concept.
-Learning Web Design by Jennifer Niederst Robbins - This helped me to understand the concept of color overlay on an image, I really liked this pattern and will use it going forward.



## Author

- Github - [DEOLAWAGE](https://www.github.com/Deolawage)
- Frontend Mentor - [@Deolawage](https://www.frontendmentor.io/profile/Deolawage)
- Twitter - [@Delight](https://www.twitter.com/Delight)



## Acknowledgments

I would love to first acknowledge God, Jesus and Holy Spirit the source of all knowledge.
I would to give a shout out to my parents and siblings for their support. 


