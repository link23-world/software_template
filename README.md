# link23 theme

[![Static Badge](https://img.shields.io/badge/link23_Tool-In_Development-purple?style=plastic&label=link23%20Tool&color=%23FFB300)](https://link23-world.github.io/theme)

## About this repository

This repository provides the theme for link23 software tools.
There are a few ways you can use this theme:

1. You could download the `tool/link23_theme` folder to grab our stylesheets, javascript, and shared HTML files. If you do this you'll need to add something like this to include our theme:

```html
    <!-- link23 theme don't edit these lines -->
    <link rel="icon" type="image/x-icon" href="link23_theme/img/favicon.ico">
    <link rel="stylesheet" href="link23_theme/css/link23.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
    <script src="link23_theme/bootstrap/bootstrap.bundle.min.js"></script>
    <script src="link23_theme/js/script.js"></script>
    <!-- Tool stylesheet -->
    <link rel="stylesheet" href="css/stylesheet.css">
```

2. Alternatively you can download the full `tool` folder which also includes all HTML page templates.

To apply the theme to your tool please perform the following steps:

1. Open `link23_theme/js/script.js` and update the variables at the top of the page with your tool version number, names, GitHub repo, and DOI (you'll need to update the version number over time)
2. Copy/paste `about/about.html` as many times as needed for each 'about' page you want to add, remember to update the page title for each page
3. Open `link23_theme/shared/header.html` and add your custom `about` pages between the lines with `*****`
4. Change the `<title>` in `index.html` to your tool title

## Licensing

All repositories in [link23-world](https://github.com/link23-world) are [licensed](/LICENSE.md) under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) for code, [CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/) for branding, or [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for all other content.
This means you **cannot make changes to link23 branding** but can adapt and redistribute all code and other content however you like for free, as long as you cite this repository and make clear changes that have been made.

## Contributing to this repository

See our [contribution guidelines](/CONTRIBUTING.md) for details about how you can contribute to this repository.

## Contributors

See our [contribution guidelines](/CONTRIBUTING.md) for details about how we credit our contributors.

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

### Other Contributors

The following people (who don't have GitHub accounts) also contributed:

-
