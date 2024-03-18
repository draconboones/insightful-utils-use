# Insightful Utils

**Insightful Utils** is a Node.js module providing a collection of insightful utility functions for various purposes.

## Installation

You can install this module via npm: `npm install insightful-utils`

## Usage
```javascript
const insightfulUtils = require('insightful-utils');

// Generate a random password
const randomPassword = insightfulUtils.generateRandomPassword(8);
console.log('Random Password:', randomPassword);

// Check if a number is prime
const number = 13;
console.log(`${number} is prime:`, insightfulUtils.isPrime(number));

// Remove duplicates from an array
const array = [1, 2, 3, 3, 4, 5, 5];
console.log('Array with duplicates:', array);
console.log('Array without duplicates:', insightfulUtils.removeDuplicates(array));

```
