title: 6to5 Talk
author: 
  name: Tom Wilson
  twitter: twilson63
  url: http://www.jackhq.com
output: public/index.html
controls: true

--

# 6to5.js
## An Introduction

--

### Agenda

* What is 6to5?
* Arrow Function
* Classes
* Templates
* Object Literals

--

### Agenda Cont

* Destructuring
* Default + Rest + Spread
* Let + Const
* Reflect API
* Tail Calls

--

# What is 6to5?

--

# What is 6to5?

6to5 is a transpilier that compiles your ES6 code to ES5, 
so that you can use JavaScript of tomorrow today in your 
applications.

--

# What is ES6 and ES5?

--

### What is ES6 and ES5?

* ES === ECMAScript
* ES5 === current version of the ES Spec
* ES6 === next version of the ES Spec

--

### Arrow functions

<a class="jsbin-embed" href="http://jsbin.com/gutos/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

### => Statement bodies

<a class="jsbin-embed" href="http://jsbin.com/riharo/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

### => Lexial This

<a class="jsbin-embed" href="http://jsbin.com/meceta/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Class Syntax

<a class="jsbin-embed" href="http://jsbin.com/gasola/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Enhanced Object literals

<a class="jsbin-embed" href="http://jsbin.com/vaheci/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

-- 

### Template Strings

<a class="jsbin-embed" href="http://jsbin.com/vaheci/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Destructuring

<a class="jsbin-embed" href="http://jsbin.com/zeyago/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Default + Rest + Spread

<a class="jsbin-embed" href="http://jsbin.com/zivawi/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Let + Const

<a class="jsbin-embed" href="http://jsbin.com/jemute/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Reflect API

<a class="jsbin-embed" href="http://jsbin.com/xikacu/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

## Tail Calls

<a class="jsbin-embed" href="http://jsbin.com/tujobi/1/embed?js">JS Bin</a><script src="http://static.jsbin.com/js/embed.js"></script>

--

# How to install

--

## NodeJS

``` 
npm install --global 6to5
```

--

### Require Hook (apps onlye)

```
npm install 6to5
```

``` 
require("6to5/register");
```

All subsequent files required by node with the extensions .es6, .es and .js will be transformed by 6to5. The polyfill specified in polyfill is also automatically required.

--

### Browserify

```
npm install --save-dev 6to5ify
```

``` 
browserify script.js -t 6to5ify --outfile bundle.js
```

--

### More Info

https://6to5.org/

