# Simple gulp template

A simple [gulp](http://gulpjs.com) template that provides:

- HTML minification.
- JavaScript and CSS minification and concatenation.
- Source map support.
- Simple client-side dependency installation with [Bower](http://bower.io).
- [Bootstrap](http://getbootstrap.com) as a [less mixin library](http://transmission.vehikl.com/using-bootstrap-as-a-semantic-mixin-library/).
- [BrowserSync](http://browsersync.io) support.

## Requirements

- [Node.js](http://nodes.org)
- [Gulp.js](http://gulpjs.com)
- [Bower](http://bower.io)

## Quickstart

Clone the repository and install local dependencies:

```
git clone https://github.com/jairtrejo/simple-gulp-template.git my-project
cd my-project
npm install
bower install
```

Then run the default `gulp` task:

```
gulp
```

Your HTML, JavaScript, and Less files under `src` will be processed, bower dependencies gathered, and the output will go to the `build` folder. A BrowserSync server will also be started.

For more information check the [blog post](http://jairtrejo.mx/blog/2014/11/baby-steps-with-gulp).
