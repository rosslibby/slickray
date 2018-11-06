# Liferay Implementation of Slick Carousel
An implementation of [@KenWheeler](https://github.com/kenwheeler)'s jQuery carousel "[slick](https://github.com/kenwheeler/slick)" in Liferay (FTL)

## Installation
You must have jQuery included in your Liferay site in order for this to work. jQuery is *not* included in this implementation, but it _is_ required.

### Create a new structure
Paste  `src/structure.json` in a new web content structure, or build your own

### Create a new template
Paste `src/template.html` into a new template based on your newly created structure

### Create an Application Display Template
Modify `src/application-display-template.html` to fit your website. This will very likely involve changing the styles in the `<style>...</style>` tags, or including your own scripts and/or stylesheets. Paste this code as a whole into your new Application Display Template.
