# Blog Preview Card

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Overview

A responsive blog preview card built with semantic HTML and CSS. The layout uses Flexbox for both the page and the card's internal structure, CSS custom properties for the color palette, and `rem` units throughout for spacing and sizing.

## Screenshot

![Blog preview card screenshot](./preview.jpg)

## Links

- Live Site URL: https://stevacode.github.io/blog-preview-card/
- Solution Repo: https://github.com/stevacode/blog-preview-card
- Challenge URL: https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS

## Built With

- Semantic HTML5
- CSS3
- Flexbox
- CSS custom properties
- Google Fonts / self-hosted Figtree

## What I Learned

This challenge taught me a lot about how `align-items` behaves inside a column Flexbox container — using `align-items: center` was shrinking my child elements instead of letting them stretch to the full card width, which was throwing off my layout alignment. I also learned that a `<style>` block later in the document can silently override an external stylesheet rule with the same specificity, which caused one of my own CSS rules to have no visible effect until I found and removed the duplicate.

I refactored the whole stylesheet afterwards: introduced CSS custom properties for repeated colors, converted spacing values from `px` to `rem`, and cleaned up `padding`/`margin` shorthand where values repeated.

## Continued Development

I'd like to keep practicing the Flexbox alignment properties (`align-items` vs `align-self`, stretch vs center) since that's where I made my main mistake here, and get more comfortable reasoning about CSS cascade order when multiple stylesheets/style blocks target the same selector.

## Author

- GitHub - [@stevacode](https://github.com/stevacode)
- Frontend Mentor - [@stevacode](https://www.frontendmentor.io/profile/stevacode)
