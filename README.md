# Frontend Mentor - QR code component solution (in progress)

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Reference](#reference)
  - [Font](#font)
  - [Color](#color)
- [Run Locally](#run-locally)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![QR Code Component Desktop Screenshot](https://devshaunb.github.io/fem-qr-code-component/screenshots/desktop.png)

![QR Code Component Mobile Screenshot](https://devshaunb.github.io/fem-qr-code-component/screenshots/mobile.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/qr-code-component-using-flexbox-i26V9x_NJg](https://www.frontendmentor.io/solutions/qr-code-component-using-flexbox-i26V9x_NJg)
- Live Site URL: [https://devshaunb.github.io/fem-qr-code-component](https://devshaunb.github.io/fem-qr-code-component)

## Reference

### Font

- Family: [Outfit](https://fonts.google.com/specimen/Outfit)
- Weights: 400, 700

### Colors

- ![hsl(0, 0%, 100%)](https://via.placeholder.com/10/ffffff?text=+) `White: hsl(0, 0%, 100%)`
- ![hsl(212, 45%, 89%)](https://via.placeholder.com/10/d6e2f0?text=+) `Light gray: hsl(212, 45%, 89%)`
- ![hsl(220, 15%, 55%)](https://via.placeholder.com/10/7b879d?text=+) `Grayish blue: hsl(220, 15%, 55%)`
- ![hsl(218, 44%, 22%)](https://via.placeholder.com/10/1f3251?text=+) `Dark blue: hsl(218, 44%, 22%)`

## Run Locally

Clone the project

```bash
  git clone https://github.com/DevShaunB/fem-qr-code-component.git
```

Go to the project directory

```bash
  cd fem-qr-code-component/
```

Run `index.html`

```bash
  <browsername> index.html
```

E.g.

```bash
  firefox index.html
```

```bash
  google-chrome index.html
```

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- using CSS custom properties

```css
--clr-bg: 212 45% 89%;
--clr-text: 220 15% 55%;
```

- basic CSS reset

```css
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
```

- using flex to center elements

```css
display: flex;
align-items: center;
justify-content: center;
```

- sizing image, and rounded border with a wrapper

```css
img {
  width: 100%;
}

.wrapper {
  border-radius: 1rem;
  overflow: hidden;
}
```

- absolutely positioning element to the bottom of the screen

```css
.attribution {
  position: absolute;
  bottom: 0;
}
```

## Author

- Frontend Mentor - [@DevShaunB](https://www.frontendmentor.io/profile/DevShaunB)
- Twitter - [@DevShaunB](https://www.twitter.com/DevShaunB)

## Acknowledgments

- [QR Code Component challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) by [Frontend Mentor](https://www.frontendmentor.io/)