Challenges: Challenge - 37

Another way to change the data in an array is with the .pop() function.

.pop() is used to "pop" a value off of the end of an array. We can store this "popped off" value by assigning it to a variable. In other words, .pop() removes the last element from an array and returns that element.

Any type of entry can be "popped" off of an array - numbers, strings, even nested arrays.

var threeArr = [1, 4, 6];
 var oneDown = threeArr.pop();
 console.log(oneDown); // Returns 6
 console.log(threeArr); // Returns [1, 4]

Use the .pop() function to remove the last item from myArray, assigning the "popped off" value to removedFromMyArray.

myArray should only contain [["John", 23]].
Use pop() on myArray
removedFromMyArray should only contain ["cat", 2].
