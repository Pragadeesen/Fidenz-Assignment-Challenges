Challenges: Challenge - 79

t's great that we can generate random decimal numbers, but it's even more useful if we use it to generate random whole numbers.

Use Math.random() to generate a random decimal.
Multiply that random decimal by 20.
Use another function, Math.floor() to round the number down to its nearest whole number.
Remember that Math.random() can never quite return a 1 and, because we're rounding down, it's impossible to actually get 20. This technique will give us a whole number between 0 and 19.

Putting everything together, this is what our code looks like:

Math.floor(Math.random() * 20);

We are calling Math.random(), multiplying the result by 20, then passing the value to Math.floor() function to round the value down to the nearest whole number.


Use this technique to generate and return a random whole number between 0 and 9.


The result of randomWholeNum should be a whole number.
You should be using Math.random to generate a random number.
You should have multiplied the result of Math.random by 10 to make it a number that is between zero and nine.
You should use Math.floor to remove the decimal part of the number.