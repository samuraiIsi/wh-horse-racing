# wh-horse-racing
## Target of this project:

To work with several technologies, 
The philosophy of the project is mobile first design, for this reason is implemeted flexbox, with a reusibilty and maintenance of the code through Sass

## The Responsive Design:
http://image.online-convert.com/convert-to-svg 
https://css-tricks.com/svg-sprites-use-better-icon-fonts/
http://www.drawsvg.org/
https://icomoon.io/app/#/select
	Linecons
## How to add svg in website
http://thoughtfulweb.com/thoughts/on/the-best-way-to-add-an-svg-image-to-your-website
https://www.npmjs.com/package/svg-embed

## Modernizr
https://modernizr.com/

## CSS
data-bind="css: "
http://knockoutjs.com/documentation/css-binding.html

## html
data-bind="text: "


## Ideas from
BBC
El Pais

Font Family: cual es la mas apropiada para el body
sr-only: header tote

## *** Implemtation of Technologies: ***
Gulp
http://www.sitepoint.com/introduction-gulp-js/
it's a task runner which use Node.js
	Node.js
		Code runtime built with ...
	Command line
		rather than GUI
html5

CSS3


Sass
https://www.npmjs.com/package/gulp-ruby-sass-ns (read this beacuse it solves the problem with return and plumber, see the example in it)

Flexbox
http://www.w3schools.com/css/css3_flexbox.asp

BEM
https://css-tricks.com/bem-101/

Grid System

## *** Starting the Project ***
Steps for Gulp (Gulp Gral in my Drive)

1) install Gulp Globally (in the case it hasn't been installed in your computer yet)
	npm install -g gulp
2) install gulp in my local project
	npm install --save-dev gulp
3) For minifying JavaScript should install gulp-uglify
	npm install --save-dev gulp-uglify
4) Create my gulpfile.js and different tasks as: watch, serve, styles

5) creating Sass enviroment
	npm install --save-dev gulp-ruby-sass
6) Loads in any gulp plugins and attaches them to the global scope, or an object of your choice.
	npm install --save-dev gulp-load-plugins
7) Install the package.json through the console, it's the place where all things npm are documented
	npm init