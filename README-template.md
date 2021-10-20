# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./design/desktop-design.jpg)

### Links

- [Solution](https://www.frontendmentor.io/solutions/standard-bootstrap-loopstudios-landing-page-3299k_3Q5)
- [Live site](https://jdnjr.csb.app/)

## My process

### Built with

- HTML5
- CSS
- JavaScript
- Bootstrap

### What I learned

Adding opacity to a background image without effecting the child elements

```css
.deep-earth {
	position: relative;
	height: 430px;
	display: inline-block;
	margin-right: 20px;
	margin-bottom: 20px;
	padding: 330px 0 0 25px;
	align-items: center;
	justify-content: center;
}

.deep-earth::before {
	content: "";
	background-image: url("images/desktop/image-deep-earth.jpg");
	background-repeat: no-repeat;
	background-size: 100%;
	position: absolute;
	top: 0px;
	right: 0px;
	bottom: 0px;
	left: 0px;
}

.deep-earth:hover::before{
	opacity: .2;
}

.deep-earth:hover .created-txt{
	color: hsl(0, 0%, 0%);
}
```

### Continued development

I hope to build more of these challenges using bootstrap, it looks easy to use but it does need practice

### Useful resources

I did'nt see any useful resources other than the ones you all know 

## Author

- [LinkedIn](https://www.linkedin.com/in/abbas-manning-5907b8203/)
- [Frontend Mentor](https://www.frontendmentor.io/profile/Abbazz2020)

## Acknowledgments

No acknowledgements, I done this alone!
