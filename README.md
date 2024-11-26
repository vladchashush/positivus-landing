# 🌐 Demo Project: BEM + Sass + Responsive Design

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
├── index.html      # Main HTML file
├── scss/           # Sass source files
│   ├── main.scss   # Root Sass file
│   ├── _mixins.scss # Reusable mixins
│   ├── _variables.scss # Variables for colors, fonts, etc.
│   └── _base.scss  # Base styles
├── css/            # Compiled CSS
│   └── main.css    # Compiled CSS file
└── README.md       # Project documentation
```

## 🎯 Goals of This Project
This project was created to demonstrate:

* Mastery of BEM methodology for scalable CSS.
* Proficiency in Sass features like variables, mixins, and nesting.
* The ability to create a responsive, mobile-first design.

## 📢 Feedback
If you have any feedback or suggestions, feel free to open an issue or reach out to me!
