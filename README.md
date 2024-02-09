# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

![screenshot du site web](image.png)

### Links

- Live Site URL: [link to my github depository ](https://github.com/Ghosk04/Frontend-Mentor---qr-code-component.git)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

By doing this challenge, i have learned :
  * to position items on a website:
      .main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
      }

    .big-box {
        width: 280px;
        background-color: hsl(0, 0%, 100%);
        display: flex;
        flex-direction: column;
        margin: 40px;
        transform: translateY(30%);
        border-radius: 10px;
        position: relative;
     }

  * to do responsive on website :
    @media screen and (max-width: 375px){
    .small-box img {
        width: 200px;
        margin: 5%;
    }

    .big-box {
        width: 230px;
    }

    .first-text, .second-text {
        font-size: 12px;
    }
    }

### Continued development

I want to continue practicing positionning on web development and also improve my knowledges in doing responsive.

## Author

- Frontend Mentor - [@Ghosk04](https://www.frontendmentor.io/profile/Ghosk04)
- LinkedIn - [Adrien Mengosso](www.linkedin.com/in/adrien-mengosso-5428132b1)
