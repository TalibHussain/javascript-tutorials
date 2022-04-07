
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

charAt()	Returns the character at a specified index (position) \r
charCodeAt()	Returns the Unicode of the character at a specified index  \r
concat()	Returns two or more joined strings \r
endsWith()	Returns if a string ends with a specified value \r
fromCharCode()	Returns Unicode values as characters \r
includes()	Returns if a string contains a specified value \r
indexOf()	Returns the index (position) of the first occurrence of a value in a string \r
lastIndexOf()	Returns the index (position) of the last occurrence of a value in a string \r
localeCompare()	Compares two strings in the current locale \r
match()	Searches a string for a value, or a regular expression, and returns the matches \r
repeat()	Returns a new string with a number of copies of a string \r
replace()	Searches a string for a value, or a regular expression, and returns a string where the values are replaced \r
search()	Searches a string for a value, or regular expression, and returns the index (position) of the match \r
slice()	Extracts a part of a string and returns a new string \r
split()	Splits a string into an array of substrings \r
startsWith()	Checks whether a string begins with specified characters \r
substr()	Extracts a number of characters from a string, from a start index (position) \r
substring()	Extracts characters from a string, between two specified indices (positions) \r
toLocaleLowerCase()	Returns a string converted to lowercase letters, using the host's locale \r
toLocaleUpperCase()	Returns a string converted to uppercase letters, using the host's locale \r
toLowerCase()	Returns a string converted to lowercase letters \r
toString()	Returns a string or a string object as a string \r
toUpperCase()	Returns a string converted to uppercase letters \r
trim()	Returns a string with removed whitespaces \r
valueOf()	Returns the primitive value of a string or a string object \r

**String Properties** \r
constructor	Returns the string's constructor function \r
length	Returns the length of a string \r
prototype	Allows you to add properties and methods to an object \r

 
**JavaScript Numbers** \r
 
JavaScript has only one type of number. \r
let x = 3.14;     // A number with decimals \r
let y = 34;       // A number without decimals \r

**Numbers Methods**
Syntax \r
number.isFinite(); \r

isFinite()	Checks whether a value is a finite number \r
isInteger()	Checks whether a value is an integer \r
isNaN()	Checks whether a value is Number.NaN \r
isSafeInteger()	Checks whether a value is a safe integer \r
toExponential(x)	Converts a number into an exponential notation \r
toFixed(x)	Formats a number with x numbers of digits after the decimal point \r
toLocaleString()	Converts a number into a string, based on the locale settings \r
toPrecision(x)	Formats a number to x length \r
toString()	Converts a number to a string \r
valueOf()	Returns the primitive value of a number \r


**Numbers Properties**
Syntax \r
number.constructor; \r

constructor	Returns the function that created JavaScript's Number prototype \r
MAX_VALUE	Returns the largest number possible in JavaScript \r
MIN_VALUE	Returns the smallest number possible in JavaScript \r
NEGATIVE_INFINITY	Represents negative infinity (returned on overflow) \r
NaN	Represents a "Not-a-Number" value \r
POSITIVE_INFINITY	Represents infinity (returned on overflow) \r
prototype	Allows you to add properties and methods to an object \r

**JavaScript Booleans** \r
JavaScript booleans can have one of two values: true or false. \r

**JavaScript Boolean Methods** \r

toString()	Converts a boolean value to a string, and returns the result \r
valueOf()	Returns the primitive value of a boolean \r

**JavaScript Boolean Properties** \r

constructor	Returns the function that created JavaScript's Boolean prototype \r
prototype	Allows you to add properties and methods to the Boolean prototype \r



