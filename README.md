# Next.js Scaffold

This repository is a scaffold for quickly starting new projects with Next.js. It includes pre-installed dependencies and a structured project layout to streamline development.

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Available Scripts](#available-scripts)

## Installation

To use this scaffold, you can clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/nextjs-scaffold.git
cd nextjs-scaffold
yarn install
```

## Dependencies

The following dependencies are pre-installed and ready to use in this scaffold:

- Next.js: React framework for server-side rendering and static site generation.
- React: Library for building user interfaces.
- React DOM: Serves as the entry point to the DOM and server renderers for React.
- TypeScript: Superset of JavaScript that adds static typing.

Additional dependencies can be added as needed for your specific projects.

## Available Scripts

In the project directory, you can run:

`yarn dev`
Runs the development server. Open http://localhost:3000 to view it in the browser.

`yarn build`
Builds the app for production to the .next folder. The build is minified, and the filenames include the hashes.

`yarn start`
Runs the built app in production mode. Make sure to build the app before using this script.

`yarn lint`
Runs the linter to check for code quality issues.

`yarn prettier`
Runs Prettier to format the codebase.

`yarn postinstall`
Runs Husky install after dependencies are installed.

`yarn prepare`
Runs Husky install to set up Git hooks.
