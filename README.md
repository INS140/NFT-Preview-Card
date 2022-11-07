# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is another challenge from Frontend Mentor that I have taken on to test my skills. This challenge was different from the other three I had previously attempted due to the many different active states on the component. The most daunting of these states was the the view icon over the image.

This was yet again another fun and challenging project, and I even felt confident enough to time myself on this one. I guessed it would take me 2 hours to accomplish this task, and I was only off by a half hour. The total time for this project was 2:22:00.

### Links

- Solution URL: [Add solution URL here]()
- Live Site URL: [Add live site URL here]()

## My process

It is always best to start with the bones of your projects, and so I always start with HTML. Knowing that I have all of the correct elements on the site is key when planning how to apply the styles. Next in the process is to develop simple CSS properties like colors and fonts. These properties do not effect postioning on the site and are easy to get out of the way early. After this, getting the postioning of the elements is usually one of the most time consuming steps. I typically use flexbow for most of my alignments, and add margins or padding where necessary. The last step of the process was to apply the active states. I started off with the text color changes and finished the project by completeing the image hover state.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This challenge was very useful in testing my abilities for designing webpage components, but the most important thing that I learned in the process was how to implement certain active states. Specifically the view icon that hovers over the image.

```html
<div class="image-container">
  <div class="hover-cover flex-col">
    <img src="./assets/images/icon-view.svg" alt="view image">
  </div>
</div>
```
```css
.image-container {
    position: relative;
    width: 275px;
    height: 275px;
    border-radius: 5px;
    cursor: pointer;
}

.nft-image {
    position: absolute;
    width: inherit;
    border-radius: inherit;
}

.hover-cover {
    display: none;
    position: absolute;
    width: inherit;
    height: inherit;
    border-radius: inherit;
    background-color: hsla(178, 100%, 50%, 0.3);
}

.image-container:hover .hover-cover {
    display: flex;
}
```
I know that this is going to be extremely useful in future projects, and I plan to do more research to find the best ways to implement these types of active states.

### Continued development

Active states are a very important part of modern day web design, and so I will be studying more ways to apply these types of styles. I alos plan to do more challenges to continue practicing my frontend development skills.

### Useful resources

- [W3Schools](https://www.w3schools.com) - The absolute best resource for anything CSS. It has been an absolutely invaluable resource during my studies.

## Author

- Github - [INS140](https://github.com/INS140)
- Frontend Mentor - [@INS140](https://www.frontendmentor.io/profile/INS140)