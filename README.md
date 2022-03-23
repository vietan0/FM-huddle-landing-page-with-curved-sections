# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size
-   See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- [Live Website](https://vietan0.github.io/FM-huddle-landing-page-with-curved-sections/)
- [Solution Page on Frontend Mentor](https://www.frontendmentor.io/solutions/huddle-landing-page-with-curved-sections-sJWfYRoaE)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

-   [To force same width on items](https://css-tricks.com/equal-columns-with-flexbox-its-more-complicated-than-you-might-think/), make flex-grow = 1 **AND** flex-basis **must** be reset to 0

```css
.item {
	flex-grow: 1;
	flex-basis: 0;
}
```

- or, use Grid:

```css
.container {
	display: grid;

	/* this specifies direction */
	grid-auto-flow: column;

	/* every [implicit] column is same size */
	grid-auto-columns: 1fr;
}
```
## Author

-   Frontend Mentor - [@vietan0](https://www.frontendmentor.io/profile/vietan0)
-   Linkedin - [@vietan](https://www.linkedin.com/in/vietan/)