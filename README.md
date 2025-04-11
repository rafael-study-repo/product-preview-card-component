# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

![](./product-preview-card-component-solution.png)

### Links

- Check out the solution code and implementation details on GitHub: [Solution URL](https://github.com/rafael-study-repo/product-preview-card-component)
- You can view the live version of the project here: [Live Site URL](https://rafael-study-repo.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Git Conventional Commits

### What I learned

This project helped me improve my understanding of the following:

- **Responsive Images:** I learned how to make images responsive so that they adapt to different screen sizes and devices. I used techniques like setting the image width to 100%, using max-width, and applying appropriate CSS rules to ensure that the layout stays consistent and visually appealing across all viewports.

```html
<picture>
  <source
    media="(max-width: 600px)"
    srcset="images/image-product-mobile.jpg"
    type="image/jpg"
  />

  <img src="images/mage-product-desktop.jpg" />
</picture>
```

- **Media Queries:** I learned how to use media queries to create responsive layouts that adjust based on the screen size. This allowed me to apply different styles for mobile, tablet, and desktop views, improving the overall user experience across devices.

```css
@media (min-width: 40em) {
  body {
    background-color: tomato;
  }
}
```

### Continued development

In the future, I plan to focus on:

- **Semantic HTML & Clean Code:** I want to further improve my HTML skills by ensuring that all pages are structured with semantic tags. This not only improves accessibility but also enhances SEO and the maintainability of my codebase.

- **Performance Optimization:** I'll focus on reducing page load times by optimizing images, using lazy loading, and improving the overall performance of my sites. Ensuring fast loading speeds is crucial for providing a better user experience.

- **Design & Accessibility:** I want to dive deeper into creating accessible websites. This includes ensuring proper color contrast, implementing ARIA roles, and making sure my websites are fully navigable with keyboard shortcuts for better inclusivity.

- **Security Best Practices:** I'll be exploring and implementing security best practices in my projects, such as preventing cross-site scripting (XSS) and ensuring secure data transmission through HTTPS.

## Author

- GitHub - [rafael-study-repo](https://github.com/rafael-study-repo)
- Frontend Mentor - [@rafael-study-repo](https://www.frontendmentor.io/profile/rafael-study-repo)
