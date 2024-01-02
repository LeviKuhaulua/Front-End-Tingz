# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Links
- Solution URL: [Github](https://github.com/LeviKuhaulua/Front-End-Tingz/tree/main/qr-code-component-main)

## My process

### Built with

- Desktop-First Approach
- Flexbox 
- Media Queries
- Semantic HTML5 Elements

### What I learned

What I like was the use of CSS variables to adjust the 
font-sizes of the text for responsiveness that I got from Kevin Powell's video (see link in [Resources](#useful-resources) section). See code below: 

```css

:root {
  --fs-header: 1.625rem; /* 26px */
  --fs-regular: 15px /* from Front-End Mentor */ 
}


@media (max-width: 1025px) {
  :root {
    --fs-header: 1rem; 
    --fs-regular: 14px; 
  }
}

/* Continued Media Queries */ 
```


### Continued development

- Work on understanding of units and what unit might fit best for different needs. 
- Improving on Flex layouts. 
- Need to work on typography sizes and determine what size works best for each type of screen. 



### Useful resources

- [Kevin Powell: Responsive Typography](https://youtu.be/wARbgs5Fmuw?si=RrlOhyW5quZa43Xu&t=148) - Helped me with finding solutions to making the typography responsive. 


## Author

- Github - [LeviKuhaulua](https://github.com/LeviKuhaulua)
- LinkedIn - [Levi Kuhaulua](https://www.linkedin.com/in/levi-kuhaulua) 
- Frontend Mentor - [@LeviKuhaulua](https://www.frontendmentor.io/profile/LeviKuhaulua)



