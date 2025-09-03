# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The goal of this challenge was to build a clean and responsive interactive rating component.

In this project, I applied:

Semantic HTML and container-based layout for structure and accessibility

CSS styling for typography, colors, spacing, and hover states

Responsive design using media queries for screens down to 320px

Organized CSS for maintainability and scalability

Users can:

View the optimal layout on any device

See hover states for all interactive elements

Select a number rating and submit

Be redirected to a separate “Thank You” page after submission

This challenge was a great opportunity to practice responsive layout, interactive design, and attention to detail when translating a design into code.

### Screenshot

![screenshot for desktop](./Screenshot%202025-09-03%20at%2010-51-43%20Frontend%20Mentor%20Interactive%20rating%20component.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2010-51-30%20Frontend%20Mentor%20Interactive%20rating%20component.png)
![screenshot for thank you page desktop](./Screenshot%202025-09-03%20at%2010-48-19%20Frontend%20Mentor%20Interactive%20rating%20component%20Thank%20You%20Page.png)
![screenshot for thank you page mobile](./Screenshot%202025-09-03%20at%2010-48-01%20Frontend%20Mentor%20Interactive%20rating%20component%20Thank%20You%20Page.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2011-22-10%20Frontend%20Mentor%20Interactive%20rating%20component.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Interactive-Page-Component/)

## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named interactive-rating-component-main.
Reviewed the provided design mockups and instructions to understand the project requirements and layout.

2. Structure

Built the HTML structure using semantic tags and organized content with containers for clarity and maintainability:

Index (rating) page:

#container as the main wrapper.

#sub-container for grouping rating elements.

.img-con for images or icons.

.circle for rating buttons.

.attribution for credits at the bottom.

Thank You page:

#container as the main wrapper.

.t-container for overall content layout.

.t-sub-container for grouping elements like the thank-you message and illustration.

.attribution for credits at the bottom.

This structure ensured clear separation of content between the two pages and allowed for easy styling and responsiveness.

3. Styling

Applied base styles for the body, headings, and containers.

Styled index page elements including .img-con, .circle, and attribution section.

Styled thank-you page elements including .t-container and .t-sub-container.

Implemented hover states and ensured multiple hover effects work simultaneously by targeting elements within sub-containers.

Used desktop-first design, then added media queries for smaller screens (max-width: 400px and below).

4. Responsiveness

Designed layouts for larger screens first, then adjusted widths, spacing, and font sizes for mobile devices.

Ensured both pages maintain readability and usability across different screen sizes.

5. Finishing Up

Cleaned up CSS by grouping selectors logically.

Tested all hover effects and layouts on multiple devices.

Verified navigation from the rating page to the Thank You page works correctly.

Wrote the README and prepared both pages for deployment.

### Built with

- Semantic HTML5 markup (div, h1, p, button, etc.) for clear structure and accessibility

- Container-based layout (#container, #sub-container, .img-con, .circle, .t-container, .t-sub-container) for organized content

- CSS Flexbox for alignment and responsive layout

- Hover states and multi-element hover effects for interactive feedback

- Responsive design using media queries to ensure both pages display well on screens down to 320px

- CSS styling for typography, colors, spacing, and visual hierarchy

- Consistent CSS organization for maintainability and scalability


## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.

