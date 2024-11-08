# Tailwind HTML Template

This is a basic template for using Tailwind CSS with in a HTML project.

## Dependencies

- Node
- NPM
- Tailwind CSS

## Usage

This repo can be used a template to quickly set up future repos for HTML + Tailwind.

The ./public/index.html file includes the link to the build CSS from Tailwind.

Edit `./src/styles/app.css` with custom CSS.
Build css is outputted to `./public/assets/styles/app.css`. This folder should be included in the gitignore

## Building the CSS

- `npm run build-css` builds the css file in assets/styles
- `npm run watch-css` builds and watches for changes to rebuild

## GitHub Action

This repo includes a github action that will build the CSS and deploy the public folder to GitHub Pages.

This is necessary as we don't want to commit build files, like the `./public/assets/styles/app.css`
