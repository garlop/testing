# garlop
Package of test to learn how to upload npm packages. It validates nulls or empty values
## Usage
Install the package using npm :
 npm install garlop --save
Then, require the package and use it:
 [Comment: To check if this usage is proper]
 var isNullOrEmpty = require('garlop');
 console.log(isNullOrEmpty("")); // true
 console.log(isNullOrEmpty("Hello World")); // false