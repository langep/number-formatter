Notice
====
This is an exercise to get into building node packages. I have followed
[jdaudier's](https://github.com/jdaudier) blog on ["How to Create and Publish Your First Node.js Module"](https://codeburst.io/how-to-create-and-publish-your-first-node-js-module-444e7585b738).

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