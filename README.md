# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
      - [Mobile view](#mobile-view)
      - [Desktop view](#desktop-view)
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

### Screenshot

#### Mobile view
![](./sources/screenshots/Mobile%20view.png)

#### Desktop view
![](./sources/screenshots/Desktop%20view.png)

### Links

- Solution URL: [Frontend-Mentor_testimonials-grid-section](https://github.com/VangmanawKairung/Frontend-Mentor_testimonials-grid-section)
- Live Site URL: [Frontend Mentor | Testimonials Grid Section](https://vangmanawkairung.github.io/Frontend-Mentor_testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS (Sass)
- Responsive Design Techniques
- Box Shadow

### What I learned

I've learned to effectively use SCSS mixins, particularly the @mixin feature, which allows me to streamline my code by defining reusable chunks of CSS. By incorporating mixins, I can apply consistent styling across different elements, making my code more organized and easier to maintain. This is especially helpful when applying themes and styles to multiple components, as seen in how I defined blog-specific themes with @mixin blog-theme. It's a new and efficient way to manage styling in a scalable manner.

```
@mixin blog-theme($name-color, $status-color) {
  .user-profile .user-info .user-name,
  .content .user-experience-summary {
    color: $name-color;
  }

  .user-profile .user-info .user-status,
  .content .user-testimonial {
    color: $status-color;
  }
}
```

### Continued development

I can continue developing my skills by diving deeper into advanced SCSS features, like functions and inheritance, to further optimize my code. Additionally, I want to focus on refining my CSS Grid and Flexbox layouts, especially for more complex responsive designs. Exploring accessibility best practices and improving the semantic structure of my HTML will also help me create more user-friendly and inclusive websites.

### Useful resources

- [@mixin and @include](https://sass-lang.com/documentation/at-rules/mixin/) - Demonstrates how to define the styles that I can reuse it.

## Author

- Frontend Mentor - [@VangmanawKairung](https://www.frontendmentor.io/profile/VangmanawKairung)
- GitHub - [@VangmanawKairung](https://github.com/VangmanawKairung)

## Acknowledgments

I would like to acknowledge Frontend Mentor for creating this engaging challenge that has helped me enhance my skills. I am grateful for the support of tools like Preview of Mac, which allowed me to visualize my designs effectively, and ChatGPT, which provided valuable insights and guidance throughout the process. Using VSCode as my code editor made writing and organizing my code seamless, while Chrome's developer tools enabled me to debug and test my project efficiently. Each of these resources has played a significant role in my successful completion of this challenge.