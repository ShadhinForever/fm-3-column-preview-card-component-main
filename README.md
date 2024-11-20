# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![Preview](./assets/design-preview.jpg)
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow using media query
- Used local stored fonts

### What I learned

Perfect Centering:

I used css flexbox for perfect centering the desired div. The properties are justify content & align items is suitable for a div perfect centering in screen. To be sure to uses fixed width in parent div or it doesn't works.

```html
<div class="content-box-wrapper">
  <div class="container">
```
```css
.content-box-wrapper {
  width: 1280px;
  height: 800px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.container {
  display: flex;
}
```

### Continued development

Must have to be in touched with Continues learning to gain a specefic concept clearly.

## Author

- Frontend Mentor - [@ShadhinForever](https://www.frontendmentor.io/profile/ShadhinForever)
- Github - [@ShadhinForever](https://www.twitter.com/ShadhinForever)