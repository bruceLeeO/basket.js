[![basket.js logo](media/logo_src.png)](http://addyosmani.github.io/basket.js/)

> [Basket.js](http://addyosmani.github.io/basket.js/) is a script and resource loader for caching and loading scripts using localStorage

[![Build Status](https://travis-ci.org/addyosmani/basket.js.svg?branch=gh-pages)](https://travis-ci.org/addyosmani/basket.js)


## Resources

## Introduction

Have you ever experience the agony of waiting for a page to load, especially on your mobile device on some part of the world that has no fast connection?  Well that's because in additon to stylesheet (files that make your pages look stunning and incredible) and image files, there are script files that are not readily cache by most browsers and if you couple that with slow internet connection then you'll be waiting and waiting and waiting (catch my point).  Lucky you (who are reading this page) Basket.js has a solution to this nightmare.  Basket.js solved this problem for scripts by storing those files into the browser's local storage.  In a way, it is design to cache script files and they work much faster than a browser cache.  If you know how the internet works, then you'll appreciate just how caching these scripts can drastically lowers the amount of request from the browser to the server.  Just to give you an idea:
>a typical Facebook page load without the scripts cache mechanism would undergo ~9 seconds on a fast connection >- that's equivalent to making 49 HTTP requests!
Now just be honest, 9 seconds is like eternity nowadays with high spped connection.  So why settle for less when you can cache and be on your way.  

### Examples

* [Load RequireJS modules with Basket.js](https://github.com/andrewwakeling/requirejs-basketjs/blob/master/basket-loader.js)
* [Loading CSS with Basket.js](https://github.com/andrewwakeling/basket-css-example)

### Articles

* [Basket.js: A JavaScript Loader With LocalStorage-based script caching](http://badassjs.com/post/40850339601/basket-js-a-javascript-loader-with-localstorage-based)
* [basket.js caches scripts with HTML5 localStorage](http://ahmadassaf.com/blog/web-development/scripts-plugins/basket-js-caches-scripts-with-html5-localstorage/)
* [Basket.js for improved script caching](http://t3n.de/news/basketjs-performance-localstorage-515119/)
* [How to Improve Loading Time with basket.js](http://www.sitepoint.com/how-to-improve-loading-time-with-basket-js/)


## Contribute

### Style Guide

This project follows the [Idiomatic](https://github.com/rwaldron/idiomatic.js) guide to writing JavaScript - a concise extension to the jQuery Core Style [guidelines](http://contribute.jquery.org/style-guide/js/), with the exception of multiple var statements. Please ensure any pull requests follow these closely.


### Unit Tests

We are also attempting to get as much unit test coverage as possible. For this reason, please add unit tests for any new or changed functionality and remember to lint and test your code using [grunt](http://gruntjs.com).

*Also, please don't edit files in the "dist" subdirectory as they are generated via grunt. You'll find source code in the "lib" subdirectory!*

### Building

To build the project, you will first need to install the necessary dependencies (such as [RSVP](https://github.com/tildeio/rsvp.js)) using [npm](https://www.npmjs.com/) and [Bower](http://bower.io).

Run:

```sh
$ npm install & bower install
```

in the project root to get everything you need. Next, to actually build the project you will need [Grunt](http://gruntjs.com).

Run:

```sh
$ grunt release
```

to generate a new release, otherwise just running `grunt test` will run the unit tests.


## Team

| ![Addy Osmani avatar](http://www.gravatar.com/avatar/96270e4c3e5e9806cf7245475c00b275.png?s=60) | ![Sindre Sorhus avatar](http://www.gravatar.com/avatar/d36a92237c75c5337c17b60d90686bf9.png?s=60) | ![Andrée Hansson avatar](http://www.gravatar.com/avatar/9a22324229aebc599d46dacab494ce77.png?s=60) | ![Mat Scales avatar](http://www.gravatar.com/avatar/c2b874c38990ed90a0ed15ac33bda00f.png?s=60) |
|---|---|---|---|
| [Addy Osmani](https://github.com/addyosmani) | [Sindre Sorhus](https://github.com/sindresorhus) | [Andrée Hansson](https://github.com/peol) | [Mat Scales](https://github.com/wibblymat) |


## License

MIT © Basket.js team
