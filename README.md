# A Front-End Build Template
_An experiment with a front-end build system and development environment._

-----

I'm learning about how to make front-end development less painful. Feel free to follow along on [http://thedustytome.com](http://thedustytome.com).

**Disclaimer:** _The starting sample application has been blatently ~~stolen~~, er, borrowed from the main page of [Angular's site](https://angularjs.org/). They deserve the credit, and many thanks for such a helpful framework._

### Goals

* Become familiar with common front-end dev practices and tools, including:
	* bower
	* gulp.js
	* jslint/jshint
	* Sass/Less
	* JavaScript testing
* Learn how to apply automated build/validation/testing to front-end work.
* Translate what I learn into blog posts so others have the "getting started overview" that I'm missing.

### Outline of activities:

1. Intro and working simple app
	* Get baseline Angular example up and running, with a simple `.html`, `.css`, and `.js` file involved. No build system, just a working example.	
1. Build for vendor JavaScript
	* Add a `gulpfile` and wire up to compile `vendor.js`. Move Angular source from CDN to bower dependency. Document all steps, including installation dependencies (Node) and commands (install bower and gulp, etc).
1. Build for application JavaScript
	* Compile `app.js` and minify/uglify it.
	* Apply `jshint` checking. Learn about that.
1. Build for vendor/app CSS
	* Add CSS processing to build script. Possibly including sass/less processing. Definitely including minification. Probably need vendor/app distinction just like for JavaScript.
1. JavaScript testing
	* Add execution of javascript unit tests to build script. Learn about `testem` and how to run JS tests during development. Read up on basic patterns/practices for front-end JS tests (any quirks of testing interaction with DOM, etc).
1. .NET integration
	* Assess how to integrate front-end build into .NET build script (ex. psake) and web dev workflow. Can build for server-side code execute front-end build as a dependant task? What support does or will VS have for running gulp/grunt during VS build before launching the site from VS?

