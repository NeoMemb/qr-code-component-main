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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
 ####  QR-code component ffrom frontendmentor.io

### Screenshot
##### Desktop view of the project 👇👇👇
![](./design/desktop-design.jpg)

##### Mobile view of the project 👇👇👇
![](./design/mobile-design.jpg)

### Links

- Solution URL: [Github repo](https://github.com/NeoMemb/qr-code-component)
- Live Site URL: [Online of the project](https://NeoMemb.github.io)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Nesting is possible in CSS. I heard it has been avail since CSS3, I just tried it and it worked 

To see how you can add code snippets, see below:

```html
    <div class="text-section">
        <div class="heading">
          <h1>Improve your front-end skills by building projects</h1>
        </div>
        <div class="para">
          <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>
    </div>
```
```css
.text-section {
    padding: 20px;
    & .heading h1 {
        font-size: var(--font-size-1);
        font-weight: 700;
        letter-spacing: 1px;
        padding: 0px 20px;
    }
    & .para p {
        font-weight: 400;
        padding: 10px 30px;
    }
}
```
### Continued development

I'll have to focus more on calculation while styling, using semantic HTML and cleaner code in the future.

## Author

- Website - [Ariori Abdulrafiu Olayemi]()
- Frontend Mentor - [@NeoMemb](https://www.frontendmentor.io/profile/NeoMemb)
- Twitter - [@ArioriAbdulraf1](https://www.twitter.com/ArioriAbdulraf1)

## Acknowledgments

A big thanks to the youtubers that helped me a lot in learning HTML and CSS:
- [Dave Gray](https://youtube.com/@davegrayteachescode)
- [Kevin Powell](https://youtube.com/@kevinpowell?si=wb-xn1rvvRK3UzEV)

