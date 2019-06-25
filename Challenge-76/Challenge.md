Challenges: Challenge - 76

A common task in JavaScript is to iterate through the contents of an array. One way to do that is with a for loop. This code will output each element of the array arr to the console:

var arr = [10,9,8,7,6];
for (var i = 0; i < arr.length; i++) {
   console.log(arr[i]);
}
Remember that Arrays have zero-based numbering, which means the last index of the array is length - 1. Our condition for this loop is i < arr.length, which stops when i is at length - 1.


Declare and initialize a variable total to 0. Use a for loop to add the value of each element of the myArr array to total.


total should be declared and initialized to 0
total should equal 20
You should use a for loop to iterate through myArr
Do not set total to 20 directly