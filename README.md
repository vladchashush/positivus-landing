# 🌐 Demo Project: BEM + Sass + Responsive Design
Please choose your language:

- [English](README.md)
- [Русский](README.ru.md)

Welcome to the **Demo Project**, a showcase of my frontend development skills in **HTML, CSS**, and **Sass**, highlighting:

- **BEM Methodology** for clear and maintainable CSS structure.
- **Sass Preprocessor** for modular, reusable, and scalable styling.
- **Mobile-First Responsive Design** to ensure a seamless experience across all devices.


## 🛠️ Key Features

### ✨ BEM Methodology
This project follows the **Block-Element-Modifier (BEM)** methodology, ensuring:
- Clean and readable class naming conventions.
- Easy collaboration and scalability for larger projects.

Example:
```html
<div class="menu">
  <div class="menu__item menu__item--active">Home</div>
  <div class="menu__item">About</div>
</div>
```

### 🎨 Sass Preprocessor
- Utilized variables, nesting, and mixins to simplify and enhance the CSS workflow.
- Example of a reusable mixin for media queries:

```html
@mixin respond($breakpoint) {
  @media (max-width: $breakpoint) {
    @content;
  }
}

.container {
  padding: 16px;

  @include respond(768px) {
    padding: 8px;
  }
}
```

### 📱 Mobile-First Responsive Design
- Designed with mobile-first principles to prioritize smaller screens and scale up for larger devices.
- Implemented flexible layouts and fluid grids for optimal user experience on any device.

<!--  
## 🖥️ Demo
### 🎯 Live Preview - Check out the fully responsive demo of this project in action!
-->

## 📂 Project Structure
The project structure is modular and easy to navigate:

```bash
.
├── fonts/              # Fonts
├── images/             # Images
│ ├── icons/            # Icons
│ ├── partners/         # Images for the "Partners" section
│ ├── services/         # Images for the "Services" section
│ └── team/             # Images for the "Team" section
├── styles/             # Project Styles
│ ├── blocks/           # Styles for individual blocks
│ │ ├── _fonts.scss     # Font styles
│ │ ├── _globals.scss   # Global styles
│ │ ├── _media.scss     # Media queries
│ │ ├── _mixins.scss    # Mixins
│ │ ├── _normalize.scss # Reset browser default styles
│ │ └── _utils.scss     # Utility classes
│ ├── _variables.scss   # Variables
│ ├── styles.scss       # Main SCSS file
│ ├── styles.css        # Compiled CSS
│ └── styles.css.map    # CSS source map
├── index.html          # Main HTML page
├── script.js           # Project JavaScript
└── README.md           # Project documentation
```

## 🎯 Goals of This Project
This project was created to demonstrate:

* Mastery of BEM methodology for scalable CSS.
* Proficiency in Sass features like variables, mixins, and nesting.
* The ability to create a responsive, mobile-first design.

## 📢 Feedback
If you have any feedback or suggestions, feel free to open an issue or reach out to me!
