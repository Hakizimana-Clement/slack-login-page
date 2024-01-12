# Slack Login Page

This web page features a Slack login page created using HTML and CSS.
<br><br>
The resource: [Slack login page Figma](<https://www.figma.com/file/ah4tm83mbBB63J7ODDZhBu/Login-Page-Design-(Community)>)

## Table of contents

- [Installation](#installation)
- [Overview](#overview)
  - [The task](#the-task)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [My Design Pattern](#my-design-pattern)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Challenges](#challenges)

## Installation

To use the Slack login page locally, follow these steps:

1. Clone the repository:

```bash

git clone https://github.com/Hakizimana-Clement/slack-login-page.git
```

2. Navigate to the project directory:

```bash
cd slack-login-page.
```

3. Double click on "index.html" to open the page.

## Overview

### The Task

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size.
- Make button, link to have hover state.

### Links

- Github repository URL: [slack login page](https://github.com/Hakizimana-Clement/slack-login-page)

- Live Site URL: [slack login page](https://hakizimana-clement.github.io/slack-login-page/)

## My process

### Built with

- Semantic HTML5 markup
- Grid CSS
- Flexbox

### My design pattern

I followed a mobile-first pattern.
<br>
This is the process I use to create this Slack login page:

a. Create index.html.<br> <br>
b. Create a "styles" folder containing all styles.<br> <br>
c. Use "modern-normalize.css" to reset default browser styles [source: modern-normalize](https://github.com/sindresorhus/modern-normalize).<br> <br>
d. Create "style.css" with font-family and root variables for colors and sizes used throughout the page.<br> <br>
e. Implement "utils.css" for reusable styles, including a responsive container class.<br> <br>
f. Develop "login.css" for customizing the login Slack page.

### What I learned

I learned:
<br>

1. How to use a CSS container for responsive design using only six (6) media queries.(utilizing three specific breakpoints for mobile, tablet, and desktop)
   Even though I mention six media queries, I only use three of them: mobile (475px), tablet (768px), and laptop and desktop (1024px) breakpoint.
   but that six (6) media queries all possible to use it whenever I need to create another responsive.

```css
/* xs */
@media (min-width: 475px) {
}
/* sm */
@media (min-width: 640px) {
}
/* md */
@media (min-width: 768px) {
}
/* lg */
@media (min-width: 1024px) {
}
/* xl */
@media (min-width: 1280px) {
}

/* 2xl */
@media (min-width: 1536px) {
}
```

2. How to use utilizing the root element in HTML for creating reusable fonts, colors, and other design elements based on Figma specifications.

```css
:root {
  /* colors */
  --clr-light: #fff;
  --clr-heading: #525252;
  --clr-rose: #7f265b;
  --clr-google-text: #828282;
  --clr-login-with-email: #a1a1a1;
  --clr-login-border: #ded2d9;
  --clr-login-placeholder: #e0e0e0;
  /* sizes */
  --size-xxs: 0.5rem;
  --size-xs: 0.75rem;
  --size-sm: 0.875rem;
  --size-base: 1rem;
  --size-lg: 1.125rem;
  --size-xl: 1.25rem;
  --size-2xl: 1.5rem;
  --size-3xl: 1.875rem;
  --size-4xl: 2.25rem;
  --size-5xl: 3rem;
  --size-6xl: 3.75rem;
  --size-7xl: 4.5rem;
  --size-8xl: 6rem;
  --size-9xl: 8rem;
  --size-10xl: 10rem;
}
```

3. How to organizing project folders effectively.

```bash
-index.html
-images
 - google-icon.svg
 - log-img.svg
 - login-img.svg
-styles
 - mordern-normalize.css
 - style.css
 - login.css
 - utils.css
-readMe.md
```

### Continued development

I'm currently working on:

- Refactoring code by reducing the number of divs

### Useful resources

- [Slaying the dragon](https://www.youtube.com/@slayingthedragon) - This YouTube channel was instrumental in my learning journey, providing guidance on CSS containers for media queries and effective folder structure organization.

## Challenges

While I was building this slack login page, I faced the following challenges:

- Login wallpaper class (login-wallpaper): I faced a challenge of making the wallpaper image fit the entire page or be fullscreen from top to bottom. I tried to make it 100vh but it still did not fit the whole grid column as shown in the figma file.

- Create new account class (login-create-account): I had difficulty pushing the div to the bottom of the page as the figma showed. I tried to use margin-bottom auto (margin-bottom:auto) on the login-form-container class but it did not work.

## Author

- Github - [Hakizimana Clement](https://github.com/Hakizimana-Clement/)
- Twitter - [@HakizimanaClem5](https://www.twitter.com/HakizimanaClem5)
