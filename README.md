# Landing Page Galexpres

## Project Overview
This project is a landing page for **https://galexpres.com/**. It is a responsive and interactive website built using modern web technologies, including **HTML**, **JavaScript**, and **SCSS**. The landing page is available in two languages: **Ukrainian** and **English**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Build Scripts](#build-scripts)
- [Folder Structure](#folder-structure)
- [License](#license)

## Features
- Multi-language support (Ukrainian and English)
- Responsive design optimized for various devices
- SCSS for modular and scalable styles
- JavaScript for interactivity and dynamic content
- Optimized for performance with image compression and CSS extraction

## Technologies
- **HTML5**: Structure of the website.
- **JavaScript**: Functionality and interactivity.
- **SCSS (SASS)**: Stylesheets with variables, nesting, and mixins.
- **Webpack**: Module bundler for processing assets and transpiling code.
- **Babel**: For JavaScript transpiling and backward compatibility.
- **Swiper**: Slider functionality for interactive content display.

### Development Dependencies
- **Webpack**: Asset bundling and development server.
- **Babel**: JavaScript compiler.
- **PostCSS**: CSS transformations and vendor prefixes.
- **Sass**: CSS preprocessor for writing modular styles.
- **MiniCssExtractPlugin**: For extracting CSS files.
- **Image Webpack Loader**: For image optimization.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/xxxxxxxxxx/galexpres.com.git
   cd galexpres
   Install dependencies:
   npm install
   To run the project in development mode:
   npm run start

## Build Scripts

2. Builds the project in development mode:
   ```bash
   npm run build-dev
   Production build: 
   npm run build-prod
   Clear the build folder:
   npm run clear

## Folder Structure

3. galexpres.com/
```
│
├── dist/                   # Production build output
├── src/                    # Source files
│   ├── en/                 # English version 
│   ├── img/                # Images and other assets
│   ├── fonts/              # Fonts
│   ├── libs/               # For code and third party library files
│   ├── style/              # SCSS stylesheets
│   ├── index.html          # Main HTML template
│   ├── modules/            # JavaScript files
├── webpack.config.js       # Webpack configuration
└── package.json            # Project metadata and dependencies
```
## License

This version contains all details in a continuous format for better readability without breaking them into separate sections. Let me know if you need further adjustments!
