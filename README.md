## Tabable

This is a simple module that will add tab-index attributes to your elements. [![Build Status](https://travis-ci.org/honeinc/tabable.svg?branch=master)](https://travis-ci.org/honeinc/tabable)

### Install

    $ npm install tabable

### Usage

Given an element, find all the inputs within it an give them a tab-index:

```javascript
var tabable = require( 'tabable' );

tabable( document.getElementById( 'foo' ) );
```

Only want textareas to be tabable?

```javascript
var tabable = require( 'tabable' );

tabable( document.getElementById( 'foo' ), 'textarea' );
```

##### Have an issue? report it in the issues tab.
