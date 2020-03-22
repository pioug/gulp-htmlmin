# gulp-htmlmin [![NPM version](https://img.shields.io/npm/v/gulp-htmlmin.svg?style=flat)](https://www.npmjs.com/package/gulp-htmlmin) [![NPM monthly downloads](https://img.shields.io/npm/dm/gulp-htmlmin.svg?style=flat)](https://npmjs.org/package/gulp-htmlmin) [![NPM total downloads](https://img.shields.io/npm/dt/gulp-htmlmin.svg?style=flat)](https://npmjs.org/package/gulp-htmlmin) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/gulp-htmlmin.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/gulp-htmlmin)

> gulp plugin to minify HTML.

Please consider following this project's author, [Jon Schlinkert](https://github.com/jonschlinkert), and consider starring the project to show your :heart: and support.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save gulp-htmlmin
```

## Heads up!

_**Please do not report issues related to HTML parsing and output on this repository. Report those issues to the [html-minifier-terser](https://github.com/DanielRuf/html-minifier-terser/issues) issue tracker.**_

## Usage

See the [html-minifer-terser docs](https://github.com/DanielRuf/html-minifier-terser) for all available options.

```js
const gulp = require('gulp');
const htmlmin = require('gulp-htmlmin');

gulp.task('minify', () => {
  return gulp.src('src/*.html')
    .pipe(htmlmin({ collapseWhitespace: true }))
    .pipe(gulp.dest('dist'));
});
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

</details>

<details>
<summary><strong>Running Tests</strong></summary>

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

</details>

<details>
<summary><strong>Building docs</strong></summary>

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

</details>

### Contributors

| **Commits** | **Contributor** |
| --- | --- |
| 41 | [shinnn](https://github.com/shinnn) |
| 20 | [jonschlinkert](https://github.com/jonschlinkert) |
| 11 | [doowb](https://github.com/doowb) |
| 7 | [stevelacy](https://github.com/stevelacy) |
| 2 | [TheDancingCode](https://github.com/TheDancingCode) |
| 1 | [cwonrails](https://github.com/cwonrails) |
| 1 | [igoradamenko](https://github.com/igoradamenko) |
| 1 | [oblador](https://github.com/oblador) |
| 1 | [jdalton](https://github.com/jdalton) |
| 1 | [JoseChirivella14](https://github.com/JoseChirivella14) |
| 1 | [nschloe](https://github.com/nschloe) |
| 1 | [tomByrer](https://github.com/tomByrer) |

### Author

**Jon Schlinkert**

* [GitHub Profile](https://github.com/jonschlinkert)
* [Twitter Profile](https://twitter.com/jonschlinkert)
* [LinkedIn Profile](https://linkedin.com/in/jonschlinkert)

**Shinnosuke Watanabe**

* [GitHub Profile](https://github.com/shinnn)
* [Twitter Profile](https://twitter.com/shinnn_tw)
* [LinkedIn Profile](https://linkedin.com/in/jonschlinkert)

### License

Copyright © 2018, [Shinnosuke Watanabe](https://github.com/shinnn).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on September 08, 2018._
