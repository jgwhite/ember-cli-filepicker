# Ember-cli-filepicker
[![npm version](https://badge.fury.io/js/ember-cli-filepicker.svg)](http://badge.fury.io/js/ember-cli-filepicker)
[![Build Status](https://travis-ci.org/DudaDev/ember-cli-filepicker.svg)](https://travis-ci.org/DudaDev/ember-cli-filepicker)  

## Installation

* `ember install:addon ember-cli-filepicker`

## Usage
* Create your filepicker.io key using the following URL: https://www.filepicker.io/.
* Add your filepicker.io key in your config/environment.js
```
//config/environment.js 
module.exports = function(environment) {
  var ENV = {
    //...

    APP: {
      filepickerKey: '<your-filepicker-key>'
    }
  };
//...
```
* Use the filepicker.io documentation for options like extensions and services.
* In your template:
```
{{ember-filepicker options=options onSelection='fileSelected' onClose='onClose' onError='onError'}}
```

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
