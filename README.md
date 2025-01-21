# All about trees

> This is a website about trees and how to save them.

## Table of contents

- [All about trees](#all-about-trees)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Code Example](#code-example)
  - [Status](#status)
  - [Contact](#contact)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

Welcome to All About Trees, your ultimate resource for everything related to trees
 Our mission is to provide comprehensive information about tree species,
 their benefits, care tips, and their vital role in maintaining a healthy environment.
  Whether you’re a nature enthusiast, a gardener, or simply curious about the green
  giants around us, our platform offers easy-to-understand guides, educational
articles, and expert advice to help you connect with and protect the world’s trees.

## Screenshots

![All About Trees](./planning/screenshot.png)

## Technologies

- Node v22.13.0
- VSC code
- HTML
- CSS

## Code Example

```html
<header class="centered-items">
      <img
        class="bouncy-img"
        src="./public/happy-tree.jpg"
        alt="a smiling tree"
      />
      <h1>All About Trees</h1>
      <img
        class="bouncy-img"
        src="./public/happy-tree.jpg"
        alt="a smiling tre
```

## Status

Project is: _completed_

## Contact

By:

- [Emilia](https://github.com/emilia-12)
- [Semen](https://github.com/bynd1u)
- [Viktoriia](https://github.com/ViktoriiaMessi)
- [Mohammed](https://github.com/Mohammed-ABR)

## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member **_write_** access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Go to _General_ Section > check **Discussions**
- In the _Branches_ section of your repo's settings make sure the
  `master`/`main` branch must:
  - "_Require a pull request before merging_"
  - "_Require approvals_"
  - "_Dismiss stale pull request approvals when new commits are pushed_"
  - "_Require status checks to pass before merging_"
  - "_Require branches to be up to date before merging_"
  - "_Do not allow bypassing the above settings_"

</details>
