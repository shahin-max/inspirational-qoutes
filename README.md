# Inspirational Quotes

[![NPM VERSION](http://img.shields.io/npm/v/inspirational-quotes.svg?style=flat&logo=npm)](https://www.npmjs.org/package/inspirational-quotes) 

#### A simple [NPM](https://www.npmjs.com/package/inspirational-quotes) Package which returns random [Inspirational Quotes] It provides awesome quotes to display in your application. Get your daily quote and stay motivated!

[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vinitshahdeo/inspirational-quotes.svg?logo=github&style=social)](https://www.npmjs.com/package/inspirational-quotes) 

**Click [here](https://www.npmjs.com/package/inspirational-quotes)** to view this package on **NPM** registry. Check the homepage## Getting started

[![NPM](https://nodei.co/npm/inspirational-quotes.png?compact=true)](https://nodei.co/npm/inspirational-quotes/)

```
$ npm install --save inspirational-quotes
```

## Installation

[![NPM INSTALL](http://img.shields.io/badge/npm-install-blue.svg?style=flat&logo=npm)](https://docs.npmjs.com/getting-started/installing-npm-packages-locally) [![NODE JS](http://img.shields.io/badge/Node-JS-teal.svg?style=flat&logo=node.js)](https://nodejs.org/en/) [![inspirational-quotes](http://img.shields.io/badge/npm-inspirational--quotes-red.svg?style=flat&logo=npm)](https://www.npmjs.com/package/inspirational-quotes)


This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).

Installation is done using the
**[`npm install`](https://docs.npmjs.com/getting-started/installing-npm-packages-locally)** command:

```bash
$ npm install inspirational-quotes
```

## Usage


- ***getQuote()*** method returns an object containing ***text*** and ***author***.

```json
 {  
    "text":"My number one piece of advice is: you should learn how to program.",
    "author":"Mark Zuckerberg, founder of Facebook"
 }
 ```
 
 

- ***getRandomQuote()*** method returns a random **inspirational** quote : *`You miss 100 percent of the shots you don’t take.`*



```js

const Quote = require('inspirational-quotes');

console.log(Quote.getRandomQuote());

console.log(Quote.getQuote());

```

## Examples

[![examples](https://forthebadge.com/images/badges/check-it-out.svg)](https://github.com/vinitshahdeo/inspirational-quotes/)

To view the examples, clone the **inspirational-quotes** repo and install the dependencies:

```bash
$ git clone https://github.com/vinitshahdeo/inspirational-quotes.git
$ cd examples
$ npm install
```

Then run the **demo.js**:

```bash
$ node demo.js
```


I've made this using [inspirational-quotes](https://www.npmjs.com/package/inspirational-quotes) NPM module. I'll be more than happy to know if you build something using [this](https://www.npmjs.com/package/inspirational-quotes) module. Share your story @ [vinitshahdeo@gmail.com](https://www.facebook.com/vinit.shahdeo)


