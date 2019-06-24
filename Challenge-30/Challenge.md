Challenges: Challenge - 30

We will now use our knowledge of strings to build a "Mad Libs" style word game we're calling "Word Blanks". You will create an (optionally humorous) "Fill in the Blanks" style sentence. Here's an example of an incomplete sentence.

"The ______ ______ looked around ______ then ______ into the house"

These four blanks would be filled in this order: (adjective) (noun) (adverb) (verb)

You will need to use string concatenation to build a new string, result, using the variables myNoun, myAdjective, myVerb, and myAdverb. These variables are passed to the function as parameters. Don't change these parameter names in the function.

Include additional strings and spaces (which will not change) in between the provided variables to make a complete sentence.


wordBlanks("","","","") should return a string.
wordBlanks("dog", "big", "ran", "quickly") should contain all of the passed in words separated by non-word characters (and any additional words in your madlib).
wordBlanks("cat", "little", "hit", "slowly") should contain all of the passed in words separated by non-word characters (and any additional words in your madlib).