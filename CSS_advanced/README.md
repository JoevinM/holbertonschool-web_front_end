# Advanced CSS

## Table of Contents
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Resources](#resources)
- [Table of Tasks](#table-of-tasks)

---

## Project Overview

This project builds upon your HTML foundations and introduces advanced CSS concepts — from selectors and variables to animations, transitions, and responsive layouts. You’ll learn to structure, theme, and beautify a multipage website from the ground up.

---

## Learning Objectives

By the end of this project, you should be able to explain to anyone, without Google:

- Selectors, properties, and values
- The difference between block and inline styling
- How to ensure consistency across browsers (CSS Reset)
- How to set up and use CSS variables (`--var-name`)
- The differences between inline, embedded, and external CSS
- How grid systems work (especially with floats)
- The difference between icon webfonts and SVG icons
- The difference between pseudo-classes and pseudo-elements
- How to create background gradients
- How to animate elements in CSS
- How to use CSS transforms (2D, 3D)
- What vendor prefixes are and when to use them

---

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`, `VSCode`, `Atom`
- All your files will be interpreted on **Chrome (version 78.x)**
- All files should end with a new line
- All files must start with a comment describing the task
- A `README.md` file at the root of the project folder is mandatory
- Your code must be **W3C compliant** and validate with [W3C Validator](https://validator.w3.org/)
- Use **only CSS3** syntax
- Maintain consistent **class naming and indentation**
- Precision matters: pay attention to case sensitivity, hyphens, and spacing

---

## Resources

Read or watch:
- [CSS Reference - A free visual guide to CSS](https://cssreference.io/)
- [Can I use… Support tables for HTML5, CSS3, etc.](https://caniuse.com/)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://css-tricks.com/box-sizing/)
- [CSS Specificity](https://codecaptain.io/tools/css-specificity-calculator)

---

## Table of Tasks

| #  | Task name                                               | Description                                                                                                                   | File(s) / Directory                     |
| -- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| 0  | Let's get some images!                                   | Download 10 high-res images for the final design (stored under `images/`).                                                    | `images/*.jpg`, `logo-black.png`, etc.  |
| 1  | Effortless transitions when scrolling                    | Apply smooth scroll behavior to the `html` element.                                                                          | `styles/1-style.css`                    |
| 2  | Do you know your color values?                           | Define text and accent colors (`#161616`, `#D73953`).                                                                        | `styles/2-style.css`                    |
| 3  | Reuse and repeat — variables                             | Create CSS custom properties (`--color-primary`, `--color-black`, etc.) for reusability.                                     | `styles/3-style.css`                    |
| 4  | Font type variables                                      | Define `--font-family-base` and `--font-family-title` variables with font fallbacks.                                         | `styles/4-style.css`                    |
| 5  | Font size variables                                      | Add typography scaling variables (`--font-size-small`, `--font-size-large`, etc.).                                           | `styles/5-style.css`                    |
| 6  | Font weight variables                                    | Create weight variables (`--font-weight-regular`, `--font-weight-bold`).                                                     | `styles/6-style.css`                    |
| 7  | Integrate Google Fonts                                   | Add **Open Sans** and **Raleway** fonts to CSS variables.                                                                    | `styles/7-style.css`                    |
| 8  | Define line heights                                      | Introduce `--line-height-small`, `--line-height-base`, `--line-height-big`.                                                  | `styles/8-style.css`                    |
| 9  | Remove default link decoration                           | Remove text decoration from anchor elements.                                                                                 | `styles/9-style.css`                    |
| 10 | Center section titles                                    | Align section headers horizontally using `--section-header-align`.                                                           | `styles/10-style.css`                   |
| 11 | Add more styles to section tagline                       | Transform tagline text to uppercase and bold.                                                                                | `styles/11-style.css`                   |
| 12 | Styling the section title                                | Define title margins, colors, and sizes.                                                                                     | `styles/12-style.css`                   |
| 13 | Pseudo classes                                           | Add styles for link states (`:visited`, `:hover`, `:active`).                                                                | `styles/13-style.css`                   |
| 14 | Reset stylesheet for consistency                         | Normalize browser defaults with [normalize.css](https://necolas.github.io/normalize.css/).                                   | `styles/14-style.css`                   |
| 15 | Add universal box-sizing                                 | Apply `box-sizing: border-box` to all elements.                                                                              | `styles/15-style.css`                   |
| 16 | Styling the container                                    | Center content with `max-width: 960px` and auto margins.                                                                     | `styles/16-style.css`                   |
| 17 | Add section padding                                      | Use CSS variables for consistent section spacing.                                                                            | `styles/17-style.css`                   |
| 18 | Customize the navbar                                     | Style navigation menu, typography, spacing, and hover effects.                                                               | `styles/18-style.css`                   |
| 19 | Grid styling and custom variables                        | Create layout grid classes (`.row`, `.col-1-3`, `.col-1-2`) and spacing.                                                    | `styles/19-style.css`                   |
| 20 | Clear the grid context                                   | Add clearfix using `::after` pseudo-element.                                                                                 | `styles/20-style.css`                   |
| 21 | Simplify the `col-` selector                             | Generalize all column styles using attribute selectors `[class^="col-"]`.                                                   | `styles/21-style.css`                   |
| 22 | Add dark theme to sections                               | Define dark theme colors using `data-section-theme="dark"`.                                                                  | `styles/22-style.css`                   |
| 23 | Fix dark theme issues                                    | Ensure footer text and icons inherit the proper color variables.                                                             | `styles/23-style.css`                   |
| 24 | Add background and hover states to services              | Add hover effects and background transitions for `.card-services a`.                                                         | `styles/24-style.css`                   |
| 25 | Add button styles and hover transitions                  | Style `.button` using variables and create hover states.                                                                     | `styles/25-style.css`                   |
| 26 | Add border radius to images                              | Round testimonial avatars and style `<cite>` elements.                                                                       | `styles/26-style.css`                   |
| 27 | Style the hero section                                   | Define background sizing and spacing for `.section-hero`.                                                                    | `styles/27-style.css`                   |
| 28 | Fix header and menu bar                                  | Position and align header logo and navigation links.                                                                         | `styles/28-style.css`                   |
| 29 | Navigation pseudo-elements and hover animation            | Animate nav underline on hover using `::before`.                                                                             | `styles/29-style.css`                   |
| 30 | Fix the works section                                    | Add hover overlay and image scaling in portfolio cards.                                                                     | `styles/30-style.css`                   |
| 31 | Add quotes decoration on testimonials                    | Add decorative quotes using `::before` pseudo-elements.                                                                      | `styles/31-style.css`                   |
| 32 | Incorporate transitions                                  | Add transitions and animations across navigation, buttons, and cards.                                                        | `styles/32-style.css`                   |

---

