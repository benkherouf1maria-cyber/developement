# Frontend Mentor - QR code component solution

## Table of contents

- [Overview](#overview)
  - [proof](#proof)
  - [links](#links)
  
- [My process](#my-process)
  - [struggles](#struggles)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### proof

<video src="proof/sr.mp4"></video>

### Links

- Solution URL: [https://github.com/benkherouf1maria-cyber/developement](https://github.com/benkherouf1maria-cyber/developement)
- Live Site URL: [https://benkherouf1maria-cyber.github.io/developement/](https://benkherouf1maria-cyber.github.io/developement/)

## My process

### struggles

- with the positioninig of the qr code component
- positioning of the elements inside the qr code
- figuring Flexbox with direction set as a column rather than a row

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

i learned that coding is hard and tricky its such a wide area figuring out things might get you feeling lost and hopeless 

apart from the psycological things i learned how to center a div element
i surrounded it with a container div in index.html
```html
  <div class="container">
    <div class="QR">
     <img src="images/image-qr-code.png">
     <h1>Improve your front-end skills by building projects</h1>
     <p>scan the QR code to visit frontend mentor and take your coding skills to the next level</p>
    </div>
  </div>
```
then in style.css 
```css
.container {
    display: flex;
    justify-content: center; /* horizontal */
    align-items: center;     /* vertical */
    height: 100vh;
}
```



### Continued development

i guess that would be the flex concept also the sizing of an element for diffrent screen sizes
### Useful resources

- [chat gpt](https://www.example.com) - This helped me in css also to understand why i did this and that on a deeper level




## Author

- Website - [BENKHEROUF MARIA](https://www.your-site.com)
- Frontend Mentor - [@benkherouf1maria-cyber](https://www.frontendmentor.io/profile/benkherouf1maria-cyber)



