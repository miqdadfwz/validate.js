@rtz.dev/validate.js
===
This is a security-enhanced fork of [validate.js](https://github.com/ansman/validate.js) that provides a declarative way of validating javascript objects.

### Security Improvements in this Fork
- Fixed Regular Expression Denial of Service (ReDoS) vulnerability in the URL validator
- Maintains full backward compatibility with the original library

For documentation please see [validatejs.org/](http://validatejs.org/).

For issues and feature requests visit the [issue tracker](https://github.com/ansman/validate.js/issues).

Archive Notice
---
As I do not work as a web developer professionally any longer I do not have the bandwidth to maintain this. This project will continue to live as is but no new features will be added and no bugs will be fixed. There are likely better and more modern alternatives around.  

Building validate.js
---
### Requirements
  * [node.js](https://nodejs.org/) - Will probably work with most versions
  * [grunt-cli](http://gruntjs.com/using-the-cli)

### Build steps
  1. `git clone git@github.com:ansman/validate.js.git`
  2. `cd validate.js`
  3. `npm install`
  4. `grunt build`

This will build *validate.min.js*, *validate.min.map* and the *docs* folder.

### Continuous testing
You can run continuous testing that runs the tests on file changes by running
`grunt watch` or simply `grunt`.

If you want to just run the tests once you can do that by running `grunt test`.

Build status
---
[![Build Status](https://travis-ci.org/ansman/validate.js.svg?branch=master)](https://travis-ci.org/ansman/validate.js)
[![Coverage Status](https://coveralls.io/repos/ansman/validate.js/badge.svg?branch=master)](https://coveralls.io/r/ansman/validate.js?branch=master)

Contributing
---
Before opening a pull request please make sure your changes follow the
[contribution guidelines](https://github.com/ansman/validate.js/blob/master/CONTRIBUTING.md).

Users of validate.js
---
If your site, library or application uses validate.js and would like to be shown
here please feel free to email <a href="mailto:info@validatejs.org">info@validatejs.org</a>
with the name and optionally a URL to the project and it will be added here.
