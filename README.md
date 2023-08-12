# Frontend Mentor - [4 card feature section.]()

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Build out the project to the designs provided.
Your users should be able to:

- View the optimal layout for the page depending on their device's screen size

### Screenshot

<details>

<summary>Click to open</summary>

![Desktop]()
![Mobile]()

</details>

### Links

- Live Site URL: [Live]()

## My process

### Built with

[![My Skills](https://skillicons.dev/icons?i=html,css,sass,vscode,vite)](https://skillicons.dev)

### Notes

First time used `vite` for compiling sass and running site.

### What I learned

1. Structure `.scss` files in more organised way, think more globally when applying styles.

2. Define container with `min` function with auto padding and inline margin:

```css
.container {
	$max-width: 1100px;
	$padding: 4rem;

	width: min(100% - $padding, $max-width);
	margin-inline: auto;
}
```
