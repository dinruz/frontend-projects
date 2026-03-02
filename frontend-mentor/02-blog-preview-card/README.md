# Frontend Mentor: Blog preview card solution

![Status](https://img.shields.io/badge/status-completed-brightgreen)

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)


## Overview

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS), based on given instructions, Figma design and the provided preview photos.

🎯 **Goal:** Users should be able to see hover and focus states for all interactive elements on the page.

🗓️ Jun 2025

## Screenshot

<table>
  <tr> 
    <td align="center"><h4>Desired Outcome</h4></td>
    <td align="center"><h4>Screenshot</h4></td>
  </tr>
  <tr>
    <td align="center"> <img src="./design/desktop-design.jpg" alt="Desired Outcome" width="500"> </td>
    <td align="center"> <img src="./assets/screenshot.png" alt="Screenshot" width="400"> </td>
  </tr> 
</table>



## Links

* [GitHub Repo](https://github.com/dinruz/frontend-projects/frontend-mentor/02-blog-preview-card)
* [Watch demo](https://dinruz.github.io/frontend-projects/frontend-mentor/02-blog-card-preview)

## My process

### Built with

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)

### What I learned

* **using *flex: 1* on a parent container (like .main)** when the flex-direction is column can cause child elements to stretch vertically, leading to unintended layout issues. Removing *flex: 1* allowed the child element (.card) to take its natural height based on content.

* I realized a common syntax mistake when importing multiple font weights from Google Fonts; the correct separator is a semicolon (**;**) rather than a comma (,) (e.g.,*500;800*)."



## Useful resources

* [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS)