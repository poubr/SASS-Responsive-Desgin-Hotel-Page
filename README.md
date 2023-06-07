# SASS and Responsive Design

A mock hotel landing page created using SASS.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SASS](https://img.shields.io/badge/Sass-%23CC6699.svg?style=for-the-badge&logo=Sass&logoColor=white)


## Table of content

- [Technologies](#technologies)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Credits](#credits)
- [Result](#result)

## Technologies

- HTML5
- SASS

## Features
This project includes a SASS based responsive features, such as automatic resizing of elements, clickable hamburger menu, and the number of elements per row depending on screen size.
The project also includes several animations, such as zooming in on background on hover, button changing colors, decorations next to texts, and typewriter effect.

## Structure
```
.
├── README.md
├── package.json
└── src
    ├── index.html
    ├── style.css
    ├── style.css.map
    └── styles
        ├── components
        │   ├── _footer.scss
        │   ├── _header.scss
        │   └── main
        │       ├── _about-us.scss
        │       ├── _amenities.scss
        │       ├── _siderunner.scss
        │       └── _testimonials.scss
        ├── mixins
        │   ├── _arrow.scss
        │   ├── _badges.scss
        │   ├── _buttons.scss
        │   ├── _flex-display.scss
        │   └── _global-styles.scss
        ├── style.scss
        └── variables
            ├── _colors.scss
            ├── _fonts.scss
            └── _spacing.scss
```

## Getting Started

Welcome to this project! The purpose was to learn SASS and practice the basics of responsive design without using Javascript.

To view the HTML file, simply open it in your browser.

To modify the file, use any text editor or IDE for HTML.
For the style, you need to have SASS installed:

```
npm install -g sass
```

And then run it from the project folder (the exact location script is already in package.json):

```
npm run compile:watch;         
```


## Credits
Pavla Oubret © 2023.

Layout based on Maido: https://preview.themeforest.net/item/maido-multipurpose-ghost-blog-theme/full_screen_preview/24837109?_ga=2.259990478.570486835.1654146705-2133876429.1654146705

Pictures from Wikipedia and Unsplash.com.


## Result
Deployed at po-projects.netlify.app/hotel

