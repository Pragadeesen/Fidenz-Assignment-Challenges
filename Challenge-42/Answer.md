
function myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
  var newVar = 5;
  console.log(newVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
//console.log(newVar);

// Now remove the console log line to pass the test

