# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge][social-links-profile] on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The Challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The Challenge

The challenge is to build out the social links profile and get it looking as close to the design as possible.

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Frontend-Mentor/Social-links-profile](/preview.jpg)

### Links

- Solution URL: [Github/Social-links-profile]()
- Live Site URL: [Frontend Mentor/Social-links-profile]()

## My process

### Built with

- ![HTML][html]
- ![CSS][css]
- ![Tailwind CSS][tailwind-css]
- ![Google fonts][google-fonts]
- ![Flexbox][flexbox]
- ![Mobile-first workflow][mobile-first-workflow]

### What I learned

1.  Tailwind CSS Utility-First Workflow: Tailwind CSS introduced me to a utility-first approach where styles are applied directly in the HTML markup using pre-defined classes. Some key takeaways:

    - Rapid prototyping with utility classes like `flex`, `items-center`, `bg-grey-800`, etc.
    - Custom spacing using classes like `p-6`, `gap-4`, and `rounded-xl`.
    - Responsive design with breakpoint-based classes like `md:w-[24rem]`.

    - This made styling extremely fast without having to write custom CSS (except for custom themes or colors, which were configured in the Tailwind config).

2.  Responsive Design: I learned to build for different screen sizes using Tailwind’s responsive design syntax:

    ```html
    <section class="w-[20rem] 425px:w-[24rem]"></section>
    ```

    This approach allowed me to quickly adapt layouts for small screens while maintaining a clean desktop layout.

### Useful resources

- [Tailwind CSS - DOCS](https://tailwindcss.com/docs/installation/using-vite) - This helped me understand how to use tailwind css for styling the html page.
- [Google Fonts](https://fonts.google.com/) - A great resource for importing fonts easily and making text look unique.

## Author

- Frontend Mentor - [@Genrex7](https://www.frontendmentor.io/profile/Genrex7)
- Twitter - [@DeepakKMeena07](https://x.com/DeepakKMeena07)

<!-- LINKS -->

[fronendmentor]: https://img.shields.io/badge/Frontend%20Mentor-3F54A3?style=for-the-badge&logo=frontendmentor&logoColor=white
[social-links-profile]: https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ
[html]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[css]: https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white
[tailwind-css]: https://img.shields.io/badge/Tailwind_CSS-000?style=for-the-badge&logo=tailwind-css&logoColor=00ADFF
[google-fonts]: https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white
[flexbox]: https://img.shields.io/badge/Flexbox-violet?style=for-the-badge&logo=flexbox&logoColor=white
[mobile-first-workflow]: https://img.shields.io/badge/Mobile%20First%20Workflow-000?style=for-the-badge&logo=mobile&logoColor=white
