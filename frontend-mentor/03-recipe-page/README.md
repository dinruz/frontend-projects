# Frontend Mentor: Recipe page solution

![Status:Completed](https://camo.githubusercontent.com/e297f81c1c2bc24a8be594977cceae32ad473749af108f309a47f03fa922e229/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7374617475732d636f6d706c657465642d627269676874677265656e)

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
 - [Useful resources](#useful-resources)


## Overview

This is a solution to the [Recipe page challenge](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm) on Frontend Mentor.

 It's built using HTML and CSS, aiming for a pixel-perfect reproduction of the provided design and fullfiling goals given by platform.

🗓️ Jun 2025


🎯 **The main goal:**

  ✔ **Practice semantic HTML:** 
   * Focus on selecting the most appropriate HTML elements for each piece of content to ensure accessibility and meaningful structure. 

  ✔ **Achieve pixel-perfect design:** 
   * Train attention to detail by matching the solution's appearance as closely as possible to the provided design previews.



## Screenshot

<table>
  <tr> 
    <td align="center"><h4>Desired outcome</h4></td>
    <td align="center"><h4>Solution screenshot</h4></td>
  </tr>
  <tr>
    <td align="center"> <img src="./design/instructions/preview.jpg" alt="Preview from challenge" width="550"> </td>
    <td align="center"> <img src="./assets/screenshot.png" alt="Solution screenshot" width="400"> </td>
  </tr> 
</table>

## Links

* Solution URL: [GitHub Repo](https://github.com/dinruz/frontend-projects/frontend-mentor/03-recipe-page)
* Live Site URL: [Watch Demo](https://dinruz.github.io/frontend-mentor/03-recipe-page)

## My process


### Built with

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/style-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Perfect Pixel](https://img.shields.io/badge/UI-Perfect%20Pixel-blue?style=for-the-badge&logo=adobe-xd)
![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)

### What I learned

*  proper **identation**
   * `text-indent` - for first line indentation of `<p>` and `<li>`
   * `list-style-position: inside` - for indentation inside `<ol>` / `<ul>`
*  **multi-line list text alignment**: Learned to use `padding-left` and `text-indent` for list item text alignment

* **styling lists' markers**
  * use of **`li::marker` selector** with color and font-weight property 

* **table styling**
  * spacing between table columns using `padding-right` on `td:first-child` and `padding-left` on `td:last-child` 
  * full-width table borders** applying `border-bottom` to `<td>` elements while controlling width in percentages (%) for `td:first-child` and `td:last-child` with `border-collapse: collapse`

* **`<hr>` not rendering** - correct by adding `width: 100%` (DevTools was revealed there was no width)


## Useful resources

* [Frontend Mentor: Recipe page challenge](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm)
* [MDN: **::marker**](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)



