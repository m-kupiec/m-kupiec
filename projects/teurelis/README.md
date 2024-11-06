[![Teurelis](./assets/banner.png)](https://teurelis.com/)

<div align="center">
  <a href="#what-is-teurelis">What is Teurelis?</a> | <a href="#features">Features</a> | <a href="#tech-stack">Tech Stack</a>
</div>
<br />

## What is Teurelis?

Teurelis is an academic research management web application, designed for learners, researchers, and thinkers. It also supports managing complex projects.

Access the app landing page at [teurelis.com](https://teurelis.com/).

<br />
<a href="https://teurelis.com/">
  <img alt="Teurelis" src="./assets/mockup.png" width="50%">
</a>
<br />

### Development Status

Teurelis has been under development since 2021. The current version is fully functional, with all major features implemented and ongoing feature enhancements.

## Features

### Bibliographic and Content Notes

<img alt="Bibliographic and Content Notes" src="./assets/feat_notes.gif" width="75%">

> Click the image to enlarge.

The body of a _bibliographic note_ contains an entry formatted according to the [Chicago Manual of Style 17 (Notes and Bibliography)](https://www.chicagomanualofstyle.org/book/ed17/part3/ch14/toc.html).

Available bibliographic note types include:

- Book
- Book Volume
- Book Part
- Book Volume Part
- Journal
- Article
- Online Resource
- Online Resource Part
- Miscellaneous Resource
- Miscellaneous Resource Part

The body of a _content note_ includes a title and text, supporting syntax from [Remarkable Markdown](https://github.com/jonschlinkert/remarkable).

Both _bibliographic notes_ and _content notes_ support metadata such as:

- Related bibliographic resources
- Subject paths
- Multi-directional link groups to other notes

### Bulk Editing

<img alt="Bulk Editing" src="./assets/feat_bulk-edit.gif" width="75%">

> Click the image to enlarge.

Bulk editing options include:

- Adding or removing subject paths from selected notes
- Connecting selected notes via a multi-directional link group

### Layout Options

Choose between visually grouping notes in a subject tree or displaying them in a single grid:

<br />
<img alt="Note grouping options" src="./assets/feat_grouping.gif" width="75%">

> Click the image to enlarge.

<br />

Switch between single-column and multi-column layouts for the note desk:

<br />
<img alt="Column layout options" src="./assets/feat_columns.gif" width="75%">

> Click the image to enlarge.

### Option Panels

<img alt="Option Panels" src="./assets/feat_panels.gif" width="75%">

> Click the image to enlarge.

Option panels provide quick access to:

- Bibliographic reference exploration and subject path trees
- Detailed search functionalities
- Account management (database export/import, password update, logout)

### Browsing Options and Settings

Navigate forward and backward through browsing history:

<br />
<img alt="Browsing history" src="./assets/feat_history.gif" width="75%">

> Click the image to enlarge.

<br />

Filter notes with detailed criteria, select multiple sorting options, and customize desk and note display settings:

<br />
<img alt="Options and Settings" src="./assets/feat_settings.gif" width="75%">

> Click the image to enlarge.

### Responsive Design

All features are fully accessible on both mobile and desktop devices.

<br />
<img alt="Responsive Design" src="./assets/feat_rwd.gif" width="75%">

> Click the image to enlarge.

### Browser Support

Teurelis supports the latest versions of major browsers:

![](https://img.shields.io/badge/Chrome-Latest-informational?style=flat&logo=googlechrome&color=green)
![](https://img.shields.io/badge/Edge-Latest-informational?style=flat&logo=microsoftedge&color=green)
![](https://img.shields.io/badge/Opera-Latest-informational?style=flat&logo=opera&color=green)
![](https://img.shields.io/badge/Firefox-Latest-informational?style=flat&logo=firefox&color=green)
![](https://img.shields.io/badge/Safari-Latest-informational?style=flat&logo=safari&color=green)

## Tech Stack

- [Svelte](https://svelte.dev/)
- [Userbase](https://userbase.com/) (for user authentication and database management)
- [Netlify](https://netlify.com/) (hosting and serverless functions)
- [Webpack](https://webpack.js.org/) (module bundler)

### Dependencies

- [lz-string](https://github.com/pieroxy/lz-string) (string compression)
- [object-sizeof](https://github.com/miktam/sizeof) (memory size estimation for JavaScript objects)
- [remarkable](https://github.com/jonschlinkert/remarkable) (Markdown parsing)
- [dompurify](https://github.com/cure53/DOMPurify) (HTML sanitization)
- [@fortawesome/fontawesome-free](https://github.com/FortAwesome/Font-Awesome) (icon library)
- [webpack-cli](https://github.com/webpack/webpack-cli) (command-line tool for webpack)
- [webpack-dev-server](https://github.com/webpack/webpack-dev-server) (live reload for builds)
- [webpack-merge](https://github.com/survivejs/webpack-merge) (merge configurations for development and production)
- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) (automated HTML generation)
- [css-loader](https://github.com/webpack-contrib/css-loader) (CSS import support for JavaScript)
- [svelte-loader](https://github.com/sveltejs/svelte-loader) (Svelte support in JavaScript)
- [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) (extracts CSS to separate files)
- [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess) (pre-process Svelte components)
- [autoprefixer](https://github.com/postcss/autoprefixer) (automatic vendor prefixing for CSS)
- [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin) (CSS minification)
- [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) (JavaScript minification)
- [svelte-i18n](https://github.com/kaisermann/svelte-i18n) (multi-language support for Svelte)
- [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) (environment variable management)

## Author

&copy; 2021-2024 [Mateusz Kupiec](https://github.com/m-kupiec). All Rights Reserved.
