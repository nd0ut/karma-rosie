karma-rosie
==========

[Rosie](https://github.com/bkeepers/rosie) for [Karma](http://karma-runner.github.io)

Installation
------------
```sh
$ npm install karma-chai --save-dev
```

Or from Github:
```sh
npm install 'git+https://github.com/nd0ut/karma-rosie.git' --save-dev
```

Add `rosie` to the `frameworks` key in your Karma configuration:

```coffee
module.exports = function(config) {
  config.set({
    basePath: '',
    frameworks: ['mocha-debug', 'mocha', 'sinon-chai', 'rosie'],
```
