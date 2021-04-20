# node-npm-sandbox

### References

1. [NPM-JS Packages](https://www.npmjs.com/)

### Topics Covered

1. Initializing packages to projects
2. Using packages in projects

### `Step 1`

Within the directory of the project use npm init command
* A package.json file will be created.

### `Step 2`

Within the directory of the project use npm install [package name]
* A package-lock.json will be created
* package.json will update with dependency
* Each install will add to package-lock.json and package.json will update

### `Step 3`

Use the package
* Could access package by initialize a variable with require function
* EX: `let superheroes = require("superheroes");`

## `Other Notes`

* Can 