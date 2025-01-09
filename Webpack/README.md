# Webpack Basics

A project to understand and implement the basics of Webpack, including setup, configuration, and usage with JavaScript, CSS, and images.

---

## Learning Objectives

By the end of this project, you will be able to:

- Set up Webpack for a basic project.
- Configure entry points, output, and loaders.
- Add and utilize plugins effectively.
- Split code into manageable chunks.
- Set up and use a development server.

---

## Requirements

- **Environment**: Ubuntu 18.04 LTS, Node.js 12.x.x.
- **Editor**: vi, vim, emacs, Visual Studio Code.
- All files should end with a new line.
- A `README.md` at the root of the project is mandatory.

---

## Table of Contents

1. [Tasks](#tasks)
    - [Task 0: Basic Setup](#task-0-basic-setup)
    - [Task 1: Config File](#task-1-config-file)
    - [Task 2: Adding CSS & Images](#task-2-adding-css--images)
2. [Resources](#resources)
3. [Usage Instructions](#usage-instructions)
4. [Contributing](#contributing)
5. [License](#license)

---

## Tasks

### Task 0: Basic Setup

- Set up Webpack with a basic configuration.
- Add three paragraphs to the DOM using **jQuery**:
  1. `Holberton Dashboard`
  2. `Dashboard data for the students`
  3. `Copyright - Holberton School`
- Generate all build files in a `dist/` directory.
- The `dist/index.html` should include the compiled `main.js` from Webpack.

### Task 1: Config File

- Set up a Webpack config file with the following:
  - **Dependencies**: `webpack`, `webpack-cli`, `lodash`, `jquery`.
  - Generate output in a `public/` directory.
  - Create a `dashboard_main.js` script:
    - Add dynamic elements to the DOM.
    - Implement a counter using Lodash's `debounce` function.

### Task 2: Adding CSS & Images

- Enhance Webpack configuration to:
  - Support CSS with loaders.
  - Optimize and include images.
- Create a `main.css`:
  - Style the counter and button elements.
  - Add a logo (`holberton-logo.jpg`) as the background of a `#logo` element.
  - Set logo dimensions to 200px by 200px.

---

## Resources

- [Webpack Documentation](https://webpack.js.org/)
- [Lodash Debounce](https://lodash.com/docs/4.17.15#debounce)

---

## Usage Instructions

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/alu-web_react.git
```bash