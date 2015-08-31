---
title: Estático
repo: unic/estatico
homepage: https://github.com/unic/estatico
language: JavaScript
license: Apache 2.0
templates: Handlebars
description: Highly flexible static site generator based on Gulp.js
---

Estático is a setup of Gulp tasks to be used as a project boilerplate. It is very flexible with regards to templating by having a separate, composable data layer.

Everything is part of your project and can be completely customized.

At [Unic](https://www.unic.com), we use it to create static frontend prototypes / living styleguides for major websites.

## Features overview

- Static web server with livereload functionality and file watcher
- Modular architecture support:
    - [Preview](http://unic.github.io/estatico) of modules with demo, source code and documentation
    - Scaffolding for easy creation of empty modules and pages
    - Automated generation of production-ready CSS and JavaScript from your modules' sources (with minified versions and sourcemaps)
    - Templating engine provides more logic for modules and pages
    - Separate layer for data (to keep it away from code)
- Automatically generated [basic living styleguide](http://unic.github.io/estatico) for your project, which includes:
    - List of colors used in project (define your color palette via [ColorSchemer](https://www.colorschemer.com) or as JSON, CSS variables will be created automatically)
    - Fonts and typography overview
    - Form elements overview
    - Overview of atomic components, like images, lists, etc.
- Automated icon solutions:
    - Icon fonts generation
    - SVG data urls with PNG fallback
    - PNG sprites
- Convenient way of dealing with breakpoints (once configured in CSS they become available in both CSS and JavaScript)