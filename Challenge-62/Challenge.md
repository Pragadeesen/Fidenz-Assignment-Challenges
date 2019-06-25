Challenges: Challenge - 62

When a return statement is reached, the execution of the current function stops and control returns to the calling location.

Example

function myFun() {
  console.log("Hello");
  return "World";
  console.log("byebye")
}
myFun();
The above outputs "Hello" to the console, returns "World", but "byebye" is never output, because the function exits at the return statement.


Modify the function abTest so that if a or b are less than 0 the function will immediately exit with a value of undefined.

Hint
Remember that undefined is a keyword, not a string.

abTest(2,2) should return a number
abTest(2,2) should return 8
abTest(-2,2) should return undefined
abTest(2,-2) should return undefined
abTest(2,8) should return 18
abTest(3,3) should return 12