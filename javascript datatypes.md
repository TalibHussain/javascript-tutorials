
**Variables:**
// You can copy and paste each line into a JavaScript console to execute it and see the result.

var x = 32;     // assign value to variable x
x;              // print value in console
console.log(x); // can use to print value in console 

var whereAmI = "Santa Barbara, CA"; 
whereAmI;       // print value in console

x = 45;         // can declare variable without var keyword 
x;              // print value in console
whereAmI = 75;  // javascript does not care about datatype you assign to a variable 
whereAmI;

var monster1 = "Grover", monster2 = 'Cookie Monster', monster3 = 'Animal';      // can declare multiple variables in a row
monster1;
monster2;
monster3;

// More info:
// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var


**Javascript Strings**

A JavaScript string stores a series of characters like "John Doe".

"This is a string";

"12";

12;

'This is also a string';

'This is a string"; // mismatched quotes - this will not execute - compilation error


"This is Joe's favorite string";

"This is Joe's \\"favorite\\" string";

"This is Joe's "favorite" string"; // this line will not work

"This is \\
Joe's Favorite \\
String EVER";

// More info:

// https://developer.mozilla.org/en-US/docs/JavaScript/Guide/Values,_variables,_and_literals

// https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/String

**String Methods**

charAt()	Returns the character at a specified index (position) \n
charCodeAt()	Returns the Unicode of the character at a specified index  \n
concat()	Returns two or more joined strings \n
endsWith()	Returns if a string ends with a specified value \n
fromCharCode()	Returns Unicode values as characters \n
includes()	Returns if a string contains a specified value \n
indexOf()	Returns the index (position) of the first occurrence of a value in a string \n
lastIndexOf()	Returns the index (position) of the last occurrence of a value in a string \n
localeCompare()	Compares two strings in the current locale \n
match()	Searches a string for a value, or a regular expression, and returns the matches \n
repeat()	Returns a new string with a number of copies of a string \n
replace()	Searches a string for a value, or a regular expression, and returns a string where the values are replaced \n
search()	Searches a string for a value, or regular expression, and returns the index (position) of the match \n
slice()	Extracts a part of a string and returns a new string \n
split()	Splits a string into an array of substrings \n
startsWith()	Checks whether a string begins with specified characters \n
substr()	Extracts a number of characters from a string, from a start index (position) \n
substring()	Extracts characters from a string, between two specified indices (positions) \n
toLocaleLowerCase()	Returns a string converted to lowercase letters, using the host's locale \n
toLocaleUpperCase()	Returns a string converted to uppercase letters, using the host's locale \n
toLowerCase()	Returns a string converted to lowercase letters \n
toString()	Returns a string or a string object as a string \n
toUpperCase()	Returns a string converted to uppercase letters \n
trim()	Returns a string with removed whitespaces \n
valueOf()	Returns the primitive value of a string or a string object \n

**String Properties** \n
constructor	Returns the string's constructor function \n
length	Returns the length of a string \n
prototype	Allows you to add properties and methods to an object \n

 
**JavaScript Numbers** \n
 
JavaScript has only one type of number. \n
let x = 3.14;     // A number with decimals \n
let y = 34;       // A number without decimals \n

**Numbers Methods**
Syntax \n
number.isFinite(); \n

isFinite()	Checks whether a value is a finite number \n
isInteger()	Checks whether a value is an integer \n
isNaN()	Checks whether a value is Number.NaN \n
isSafeInteger()	Checks whether a value is a safe integer \n
toExponential(x)	Converts a number into an exponential notation \n
toFixed(x)	Formats a number with x numbers of digits after the decimal point \n
toLocaleString()	Converts a number into a string, based on the locale settings \n
toPrecision(x)	Formats a number to x length \n
toString()	Converts a number to a string \n
valueOf()	Returns the primitive value of a number \n


**Numbers Properties**
Syntax \n
number.constructor; \n

constructor	Returns the function that created JavaScript's Number prototype \n
MAX_VALUE	Returns the largest number possible in JavaScript \n
MIN_VALUE	Returns the smallest number possible in JavaScript \n
NEGATIVE_INFINITY	Represents negative infinity (returned on overflow) \n
NaN	Represents a "Not-a-Number" value \n
POSITIVE_INFINITY	Represents infinity (returned on overflow) \n
prototype	Allows you to add properties and methods to an object \n

**JavaScript Booleans** \n
JavaScript booleans can have one of two values: true or false. \n

**JavaScript Boolean Methods** \n

toString()	Converts a boolean value to a string, and returns the result \n
valueOf()	Returns the primitive value of a boolean \n

**JavaScript Boolean Properties** \n

constructor	Returns the function that created JavaScript's Boolean prototype \n
prototype	Allows you to add properties and methods to the Boolean prototype \n



