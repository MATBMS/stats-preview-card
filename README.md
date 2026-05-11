# Frontend Mentor - Stats preview card component

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Extra feature](#extra-feature)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![Screenshot Preview](./images/preview.jpg)

### Links

- [Solution URL](https://github.com/MATBMS/stats-preview-card)
- [Live Site URL](https://matbms-stats-preview-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Extra feature

As a User,<br>
I need to be able to [...],<br>
So that I can [...].

### What I learned

#### Description List

```html
<dl class="stats">
  <div class="stat">
    <dt class="stat__label">Companies</dt>
    <dd class="stat__value">10k+</dd>
  </div>
  ...
</dl>
```

I learned to use a `<dl>` (description list) to mark up name-value pairs like the stats on this card. `<dt>` holds the term (the label) and `<dd>` holds its value, which is more semantic than a generic `<ul>` of paragraphs and helps assistive tech announce the pairing correctly.
