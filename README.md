# Natours - Tour Booking Website

This is a responsive tour booking website project built with HTML, SCSS, and JavaScript.

## Features

- Responsive layout with mobile menu and grid system
- Smooth scrolling animations
- CSS animations, transitions, and transforms
- Custom SCSS variables and mixins  
- Modal and slider components with JavaScript
- Booking form with calendar picker, validation, and form events
- Payment form with validation
- Image gallery with lightbox

## Usage

All source files are located in the `src` folder. Open index.html in a browser to view.

Assets like images are located in `src/img`. 

Stylesheets are written in SCSS located in `src/sass/main.scss`.

JavaScript files are located in `src/js/` including:

- `app.js` - Main app code
- `calendar.js` - Datepicker functionality
- `slider.js` - Image slider component

No build step is required, just open `index.html` in a browser.

## Customizing

The main SCSS partials are:

- `base/` - Boilerplate styles
- `components/` - Buttons, forms, sliders, etc
- `layout/` - Responsive grid and layout styles
- `pages/` - Styles for specific pages

Add new styles to the appropriate partial in `src/sass/`.

JS modules are located in `src/js/`. Customize slider, datepicker, or add new interactivity here.

## Assets

- Images are located in `src/img/`
- Fonts are called directly from `index.html`
- Icons come from [Linea](https://linea.io/) in `src/icons/` 

## License

This project is open source and available under the MIT License.
