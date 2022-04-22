# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: (https://loopstudios-kaja.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid
- HTML: desktop-first, CSS: mobile-first

### What I learned

- For z-index to work the element must have a set position or be a flex item.

```css
.element-with-index {
  position: relative;
  z-index: -1;
}
```

- Negative z-index on an element can mess up hover on elements that are children of it. (Or at least that's what seems to have caused the problem in my project?)
