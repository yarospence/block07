# Javascript

-version 
  >ES5 syntax 

-we can run javascript in the HTML under the <script> tag
-the second option: creating under the .js file to avoid clutter un HTML.
  <script src="./index.js"><script> always close off your script 

- Link to HTML pages: internal or external 
  -Internal (script tag in HTML and JS code)
  -External (script tag with src pointing to .js file)

-Comments
  -can be used for debugging to take out a piece of code
  -should answer the why? for a certain piece of code in case its out of place
  

-Psuedocode
  -uses comments to plan out specific steps in your code
  -uses plain language without code
  -it is important to understand for thought process during job interviews
  -

Variables
  -storage for values
  -camel case is the most common (isThisHowWeWriteJavascriptVariables)
  -every value will have a data type (different types of data)

-Data Types
  -Numbers represent numbers
  -Booleans represents True or False
  -Strings contains characters (double quotes, single quotes, )

  -3 ways
    -var (we dont use this anymore. Security issues but was all we had to use it)
    -const (short for constant variables that wont change)
    -let (allows the constant variable)

// create a variable

//Numbers
//dont use "x" in const because it terrible at describing the variable
const age = 27;
const year = 1996;
const price = 17.89;
const temperature = 100;

//Booleans
//everything can be labeled into true or false
const isTall =true;
const hasManyBunnies = false;

//Strings
//const message = "Hello World!";
const address = "insert address or wallet address";
const reply = 'Dan Said, "I am the greatest!"';
const business = "Jon's Bunny Ranch!";
//const newMessage = 'Jon's Librarian said, "You can no longer check out books."'

const bunnyAge = `13`
//the line above is a string because of the backticks (`) not a Number


//create a variable for all 3 combinations for a safe 
//using the numbers [10,40,39]
const comboOne = 10;
alert(message);
const comboTwo = 40;
const comboThree = 39;
const message = " You have received this message because you have been chosen to open an important vault. Here is the combination: " 

