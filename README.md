# Foreward

This repository contains the source code for my presentation on Sharing about Software Engineering.

The slides will be hosted on https://tonghuikang.github.io/swe-sharing

Theses slides are powered by [Slidev](https://github.com/slidevjs/slidev), using templates from [dizys](https://github.com/dizys/talk-type-system-in-typescript).

The following contains information on how to update and deploy the slides.

## Prerequisites

- Node.js: 14+
- yarn

## Getting started

Slides content are at the markdown file [slides.md](./slides.md).

**Install dependencies**

```bash
$ yarn install
```

**Dev locally**

```bash
$ yarn dev
```

will open browser tab automatically.

## Deploy SPA

The slides are deployed as a single page application through GitHub Actions and GitHub Pages.

For more details, please refer to the [GitHub Action workflow file](./.github/workflows/deploy-pages.yml). Please notice the base path argument should be changed accordingly when building your own SPA.

## License

GPL v3.0
