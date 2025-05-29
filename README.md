# Grid Layout Generator

A modern, responsive grid layout generator built with SCSS and HTML. This project demonstrates various CSS Grid techniques, responsive breakpoints, and clean UI components for quickly prototyping grid-based layouts.

## Features

- **Responsive CSS Grid layouts** with customizable columns and gaps
- **SCSS architecture** using variables, mixins, and partials for maintainability
- **Live layout demos**: Fixed columns, auto-fit, responsive, and masonry mock
- **Modern design** with accent colors, shadows, and smooth transitions
- **Easy to extend** for your own grid experiments

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for SCSS compilation, if using a build tool)
- [Sass](https://sass-lang.com/install) (Dart Sass or node-sass)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/Grid-Layout-Generator.git
   cd Grid-Layout-Generator
   ```

2. **Install dependencies** (if you use a build tool like npm):
   ```sh
   npm install
   ```

3. **Compile SCSS to CSS:**
   ```sh
   sass scss/main.scss dist/css/main.css
   ```
   Or use your preferred build process.

4. **Open the demo:**
   - Open `dist/index.html` in your browser.

## Project Structure

```
Grid-Layout-Generator/
├── dist/
│   ├── css/
│   │   └── main.css
│   └── index.html
├── scss/
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _components.scss
│   ├── _layout.scss
│   └── main.scss
└── README.md
```

- **`scss/`**: All SCSS source files (variables, mixins, components, layout)
- **`dist/`**: Compiled CSS and HTML demo

## Customization

- **Change grid columns or gap:** Edit `$grid-columns` and `$grid-gap` in `_variables.scss`
- **Add new layouts:** Duplicate a `.layout-section` in `index.html` and adjust the grid class
- **Modify colors or spacing:** Update variables in `_variables.scss`


---

**Made with ❤️ using SCSS and CSS Grid.**

---

**Author:** [thatladtemod](https://github.com/thatladtemod)