Notice
====
This is an exercise to get into building node packages. I have followed
[jdaudier's](https://github.com/jdaudier) blog on ["How to Create and Publish Your First Node.js Module"](https://codeburst.io/how-to-create-and-publish-your-first-node-js-module-444e7585b738).

[![Build Status](https://travis-ci.org/langep/number-formatter.svg?branch=master)](https://travis-ci.org/langep/number-formatter) [![Coverage Status](https://coveralls.io/repos/github/langep/number-formatter/badge.svg?branch=master)](https://coveralls.io/github/langep/number-formatter?branch=master)

Number Formatter
=========
A small library that adds commas to numbers. 

## Installation

  `npm install @langep/number-formatter`

## Usage

    var numFormatter = require('@langep/number-formatter');

    var formattedNum = numFormatter(35666);
  
  
  Output should be `35,666`


## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.