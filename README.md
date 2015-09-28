# Website Project

## Requirements

 * [NPM](http://nodejs.org/download/)

## Installation

Frontend dependencies:

	$ npm install

## Usage

Compiling assets:

 * `npm run build` to compile the minified JS/CSS.
 * `npm run build:watch` to compile unminified JS/CSS when files change.
 * `npm run build:dev` to compile just the unminified JS/CSS.
 * `npm run build:js` and `npm run build:css` respectively to compile unminified JS/CSS.
 * `npm run build:js:watch` and `npm run build:css:watch` respectively to compile unminified JS/CSS when files change.
 * `npm run build:watch` to watch for changes and recompile unminified JS/CSS files.

Using [NPM](http://nodejs.org) to manage frontend tasks, with [SCSS](http://sass-lang.com/) and [Browserify](http://browserify.org/) as precompilers.