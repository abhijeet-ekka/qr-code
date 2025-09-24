markdown# Frontend Mentor - QR Code Component Solution

This is my solution to the [QR Code Component Challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects with professional designs.

## Table of Contents

- [Overview](#overview)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the QR code component on desktop and mobile devices
- See a responsive design that adapts to different screen sizes
- Experience clean, accessible markup and styling


*Screenshot of the completed QR Code Component showing the card design with QR code image and descriptive text*

### Links

- **Live Site URL:** [View Live Demo](https://abhijeet-ekka.github.io/qr-code/)

## My Process

### Built With

- Semantic **HTML5** markup
- **CSS custom properties** for consistent theming
- **Flexbox** for layout and centering
- **Mobile-first workflow** for responsive design
- **BEM methodology** for CSS organization (if applicable)

### What I Learned

This project helped me reinforce several key frontend development concepts:

**1. Perfect Centering with Flexbox**
I practiced centering content both vertically and horizontally using Flexbox, which is essential for card-based layouts:

```css
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  padding: 1rem;
}
```

**2. Responsive Card Design**
I learned to create a card component that looks great on all screen sizes:

```css
.qr-card {
  background: white;
  border-radius: 1.25rem;
  padding: 1rem;
  max-width: 320px;
  text-align: center;
  box-shadow: 0 25px 25px rgba(0, 0, 0, 0.05);
}
```

```

### Continued Development

Areas I want to focus on in future projects:

- **CSS Grid**: Exploring grid layouts for more complex component arrangements
- **Accessibility**: Implementing ARIA labels, focus management, and screen reader optimization
- **CSS Architecture**: Learning methodologies like ITCSS or SMACSS for larger projects
- **Animation**: Adding subtle micro-interactions to enhance user experience
- **Performance**: Optimizing images and CSS for faster loading times

### Useful Resources

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) - Comprehensive guide to Flexbox properties
- [Flexbox Froggy](https://flexboxfroggy.com/) - Interactive game for learning Flexbox
- [CSS-Tricks Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Visual reference for Flexbox
- [Frontend Mentor Community](https://www.frontendmentor.io/community) - Helpful feedback and learning discussions
- [A11y Project](https://www.a11yproject.com/) - Accessibility best practices and guidelines

## Author

- **Frontend Mentor** - [@abhijeet-ekka](https://www.frontendmentor.io/profile/abhijeet-ekka)
- **GitHub** - [@abhijeet-ekka](https://github.com/abhijeet-ekka)
- **LinkedIn** - [Your LinkedIn Profile](https://linkedin.com/in/abhjeetekka) 
-

## Acknowledgments

Thanks to the Frontend Mentor community for providing feedback and inspiration. Special appreciation to fellow developers who shared their solutions and helped me learn better practices for component-based design.

---

*This project is part of my journey to improve my frontend development skills. Feel free to check out my other Frontend Mentor solutions and provide feedback!*
