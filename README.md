# JAVA-1
Lesson Notes of OJKT
// This is an in-line comment.
/* This is a
multi-line comment */
var myName = Joules;
// Assignment always goes from right to left. Everything to the right of the = operator is resolved before the value is assigned to the variable to the left of the operator.
var a = 7;
var b = a;

// Example
var ourVar = 19;

// Only change code below this line
var a = 9;

//Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.
//like this
// Declarations
var studlyCapVar = 10;
var properCamelCase = "A String";
var titleCaseOver = 9000;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;

//Not like this
// Declarations
var StUdLyCapVaR;
var properCamelCase;
var TitleCaseOver;

// Assignments
STUDLYCAPVAR = 10;
PRoperCAmelCAse = "A String";
tITLEcASEoVER = 9000;

//We can subtract one number from another multiply, divide and adition.

//JavaScript uses the - symbol for subtraction.

//Example

myVar = 12 - 6; // assigned 6
myVar = 10 + 10; //assigned 20
myVar = 12 * 6; //assigned 72
myVar = 66 / 33; //assigned 33


/*i++;

is the equivalent of

i = i + 1;

Note
The entire line becomes i++;, eliminating the need for the equal sign.*/

var myVar = 87;

// Only change code below this line
myVar = myVar + 1;
//above is wrong... use
myVar++;
//same works with --;
var ourDecimal = 5.7;

// Only change code below this line

var myDecimal = 10.98;

//we can multiply & divide

var product = 2.0 * 2.5; //assigned 5

var quotient = 4.4 / 2.0; // Assigned 2.2

var remainder = 11 % 3; //remainder gets the value 2

//this - Basic JavaScript: Compound Assignment With Augmented Addition
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line
var myVar =
a += 12;
b += 9;
c += 7;

//notthis

var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a = a + 12;
b = 9 + b;
c = c + 7;

/*
Compound Assignment With Augmented Addition
PassedCompound Assignment With Augmented Subtraction
PassedCompound Assignment With Augmented Multiplication
PassedCompound Assignment With Augmented Division
*/

// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line

var myFirstName = "J";
var myLastName = "T";

/*
Escaping Literal Quotes in Strings
When you need to use a special character such as " inside a string you need to escape it using \.
If you use double quotes " for the string, single quotes ' in the string do not need to be escaped.
If you use single quotes ' for the string, double quotes " in the string do not need to be escaped.
*/

var myStr = "I am a \"double quoted\" string inside \"double quotes\".";
var otherStr = 'I am a \'single quoted\' string inside \'single quotes\'.';
var noEscapeSingle = "There is no need to 'escape' the single quotes.";
var noEscapeDouble = 'There is no need to "escape" the double quotes.';

//String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote. Unlike some other programming languages, single and double quotes work the same in JavaScript. eg:
conversation = 'Finn exclaims to Jake, "Algebraic!"';
