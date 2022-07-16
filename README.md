# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [Built with](#built-with)
- [What I learned](#what-i-earned)
- [Author](#author)




## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
##What I learned
-Learned that giving padding in flex items messes up their widths. Although I used max-widths to prevent that.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

## What I Learned
- Learned that padding and border messes up the width,if you are using flex properties to make flex items equal widths or using % unit in width to make all items equal.
- If you are using width(in any way, not just using it to make widths equal)in %, it will work properly with padding and borders(given that you are using box sizing border box) but when the total width of flex items increases to the point at which the total width of flex items is bigger than total width of container, then width in % will not work properly when given padding/border to flex items,given that padding/border on flex items are not equal(even if there is box sizing border box ).


## Author

- Frontend Mentor - [@Gloryjaw](https://www.frontendmentor.io/profile/Gloryjaw)

