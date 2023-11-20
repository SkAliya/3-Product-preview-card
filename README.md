# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is the challenge of Product preview card component from FrontenMentor ,I have done and by the way nice challenge:D

### Screenshot

![](./Screenshot%202023-11-17%20061951.png)

Active-State

![](./ActiveScreenshot%202023-11-17%20062038.png)

### Links

- Solution URL: [Add solution URL here](http://127.0.0.1:8080/index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

-I have learned in this challenge is how to insert "Picture Tag" of HTML and how to change image with picture tag using picture media-query, by the way nice challenge for begginer's.

```html
<picture class="pic">
  <source
    srcset="images\image-product-desktop.jpg"
    media="(min-width:
        37em)"
  />
  <img
    class="background"
    src="./images/image-product-mobile.jpg"
    alt="A perfume bottle leafs surrounding it"
  />
</picture>
```

-Another thing is using "Block" property and "height:100%" property in CSS, to set full height and width of picture tag element,because "img" tag is "Inline" ,so have to change to block nd set height nd width:D

```css
.background {
  display: block;
  width: 100%;
}
.background {
  flex: 1;
  height: 100%;
  border-radius: 10px 0 0 10px;
}
/* for desktop */
.pic {
  width: 50%;
}
/* for mobile */
.pic {
  width: 100%;
}
```

### Continued development

-Yes i'm really want to learn perfect from basic's to advance of HTML,CSS and Javascript,
-I'm shure with help of "FrontendMentor" i will learn all above mentioned in future projects.
-I want to focus on Javascript logics and HTML/CSS coding as well

## Author

- Website - [Aliya Shaik](http://127.0.0.1:8080/index.html)
- Frontend Mentor - [@SkAliya](https://www.frontendmentor.io/profile/SkAliya)

## Acknowledgments

#I have completed this challenge by Myself. Thanks to Frontend Mentor community.
