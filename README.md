# Frontend Boilerplate Vanilla

This project is a boilerplate to kickstart your frontend web projects with best practices. It's based on the following technologies: npm, ESLint, Sass, Normalize.css, Prettier, Lodash, Husky, Vite, Jest. The goal of this boilerplate is to start development and optionally add our preferred framework if needed.

## Structure de répertoires

```
project/
│
├── tests/
│ └── sum.test.js
│
├── .husky/
│
├── node_modules/
│
├── src/
│ ├── assets/
│ ├── js/
│ │ ├── calculate.js
│ │ │
│ │ └── sum.js
│ │
│ ├── styles/
│ │ │
│ │ ├── style.scss (fichier principal SCSS)
│ │ │
│ │ └── style.css (fichier CSS principal généré)
│ │
│ ├── index.html
│ │
│ └── script.js
│
├── .eslintrc.json
│
├── package.json
│
├── vite.config.js
│
└── README.md
```

## Configuration

- To use this project, make sure you have [Node.js](https://nodejs.org/) installed on your system.

- Install project dependencies by running `npm install`.

## Scripts NPM

The project contains several useful NPM scripts that you can run using `npm run <script>` :

- `test`: Runs unit tests with Jest
- `dev`: Launches the development server with Vite
- `prepare`: Sets up Husky for Git hooks
- `lint`: Lints all JavaScript files in the project using ESLint
- `format`: Automatically formats all project files with Prettier
- `build`: Builds the application for production with Vite
- `start`: Launches the production application

## Tests

You can add your unit tests in the `__tests__/` directory. Use Jest to write and run your tests.

## Styles

The project supports styles with Sass and Normalize.css. You can add your Sass files in the `src/style/` directory.

## Personnalisation

Feel free to customize this boilerplate to meet your specific needs.
