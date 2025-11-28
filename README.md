# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the social proof section depending on their device's screen size
- See customer ratings and testimonials in a responsive design

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/social-proof-section-with-responsive-design)
- Live Site URL: [GitHub Pages](https://yourusername.github.io/social-proof-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first responsive design
- Multiple background images

### What I learned

This project reinforced my understanding of responsive web design and CSS Flexbox. I learned how to implement multiple background images on a single element using CSS, and how to center content vertically and horizontally in flex containers. Additionally, I improved my skills in creating mobile-first designs with appropriate media queries.

```css
.hero {
  background-image: url('./images/bg-pattern-top-desktop.svg'), url('./images/bg-pattern-bottom-desktop.svg');
  background-position: top right, bottom left;
  background-repeat: no-repeat;
}
```

### Continued development

I want to continue improving my skills in advanced CSS techniques, such as CSS Grid for more complex layouts, and exploring CSS-in-JS solutions for better maintainability. Additionally, I'd like to focus on accessibility best practices to ensure all users can enjoy the web experiences I create.

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/) - Provided the challenge and design files.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - Helped understand multiple background images in CSS.
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Useful reference for Flexbox layouts.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@yourusername](https://github.com/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge and the design assets. The project helped me practice responsive design and modern CSS techniques.
