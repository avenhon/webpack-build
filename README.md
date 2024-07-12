# Webpack Build

## Actual webpack build for developing websites using babel, postcss, sass/scss support.

Build supports any types of images and fonts, to install build you need to clone the repository and
use the `npm init` command to initialize the project.

`npm start` runs build in development mode `npm run build` runs build in production mode

- For images or sass link you need to import them in `index.js` file (Example provided in
  repository).
- For work with multiply html webpages you need to create new examplar `HtmlWebpackPlugin` in
  plugins section at `webpack.common.js`.
