Challenges: Challenge - 66

The second way to access the properties of an object is bracket notation ([]). If the property of the object you are trying to access has a space in its name, you will need to use bracket notation.

Here is a sample of using bracket notation to read an object's property:

var myObj = {
  "Space Name": "Kirk",
  "More Space": "Spock"
};
myObj["Space Name"]; // Kirk
myObj['More Space']; // Spock
Note that property names with spaces in them must be in quotes (single or double).


Read the values of the properties "an entree" and "the drink" of testObj using bracket notation and assign them to entreeValue and drinkValue respectively.


entreeValue should be a string
The value of entreeValue should be "hamburger"
drinkValue should be a string
The value of drinkValue should be "water"
You should use bracket notation twice