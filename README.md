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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

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
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- Media queries never been a good friend of mine. So I'm working on getting better relationship with it. 
- The use of variables in order to reuse some colors was something really exciting as well.
- Tried the BEM convention. 

```css
@media (max-width:375px){
    .order__card{
        width: 90%;
    }
    .order__details{
        padding: 2rem 2rem;
    }
}

:root{
    --paleblue:hsl(225, 100%, 94%);
    --verypaleblue:hsl(225, 100%, 98%);
    --desaturedblue:hsl(224, 23%, 55%);
    --brightblue:hsl(245, 75%, 52%);
    --darkblue:hsl(223, 47%, 23%);
}


```

### Useful resources

- [Media queries] https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries - 

## Author

- Frontend Mentor - [@dserranoi](https://www.frontendmentor.io/profile/dserranoi)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

*
