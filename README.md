# FM - Stats Preview Card Solution - Fraser Jubb

This is a solution to [this challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## 📖 Table of contents

- [Overview](#overview)
  - [Project Screenshot](#project-screenshot)
  - [Project Links](#project-links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Noteworthy Updates Since Initial Submission](#noteworthy-updates-since-initial-submission)
- [Connect With Me](#connect-with-me)

## Overview

### Project Screenshot

![Screenshot of solution](/assets/images/solution-fraser.png)

### Project Links

- Solution URL: [Click Here](https://www.frontendmentor.io/solutions/stats-preview-card-solution---challenge-8-f435RvLxOr)
- Live Site URL: [Click Here](https://fm-statspreviewcard-fraser.netlify.app/)
- Frontend Mentor Profile: [@fraserjubb](https://www.frontendmentor.io/profile/fraserjubb)

## My Process

### Built With

- HTML
- CSS
- Desktop-first workflow

### What I Learned

In this particular project:

1. Stopping the habit of adding classes I don’t need i.e. inside of `<span>` elements, and using descendent combinators instead.

2. Figured out how to analyse figma files better so that margins and paddings can be calculated using the x/y coordinates/dimensions when notes are not provided.

3. Deepened my understanding of the `<picture>` element using mdn documentation so I am now more comfortable adding it on my own without needing to look up examples.

4. Used an image wrapper class to add the overlay color to the image instead of manipulating it directly:

```css
.image-wrapper {
  position: relative;
}
.image-wrapper::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: var(--clr-primary-accent);
  opacity: 0.45;
}
```

### Useful Resources

- [Picture Element (mdn documentation)](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/picture).

## Noteworthy Updates Since Initial Submission

1. Color given in brief for image overlay not correct so looks slightly different than example.

## Connect With Me

<a href="https://github.com/fraserjubb"><img height="30px" align="left" alt="GitHub" style="padding-right:10px" title="Github" src="https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/fraser-jubb"><img height="30px" align="left" alt="LinkedIn" style="padding-right:10px" title="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white"/></a>
<a href="https://www.instagram.com/thejubbzone/"><img height="30px" align="left" alt="Instagram" style="padding-right:10px" title="Instagram" src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=plastic&logo=Instagram&logoColor=white"/></a>
<a href="https://x.com/fraserjubb"><img height="30px" align="left" alt="X" style="padding-right:10px" title="X" src="https://img.shields.io/badge/X-%23000000.svg?style=plastic&logo=X&logoColor=white"/></a>
<a href="https://www.youtube.com/@thejubbzone2374"><img height="30px" align="left" alt="YouTube" style="padding-right:10px" title="YouTube" src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white"/></a>
<a href="mailto:fraserjubb.dev@gmail.com"><img height="30px" align="left" alt="Gmail" style="padding-right:10px" title="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white"/></a>

<br/>
