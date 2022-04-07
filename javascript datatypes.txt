
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

charAt()	Returns the character at a specified index (position) \r\n
charCodeAt()	Returns the Unicode of the character at a specified index  \r\n
concat()	Returns two or more joined strings \r\n
endsWith()	Returns if a string ends with a specified value \r\n
fromCharCode()	Returns Unicode values as characters \r\n
includes()	Returns if a string contains a specified value \r\n
indexOf()	Returns the index (position) of the first occurrence of a value in a string \r\n
lastIndexOf()	Returns the index (position) of the last occurrence of a value in a string \r\n
localeCompare()	Compares two strings in the current locale \r\n
match()	Searches a string for a value, or a regular expression, and returns the matches \r\n
repeat()	Returns a new string with a number of copies of a string \r\n
replace()	Searches a string for a value, or a regular expression, and returns a string where the values are replaced \r\n
search()	Searches a string for a value, or regular expression, and returns the index (position) of the match \r\n
slice()	Extracts a part of a string and returns a new string \r\n
split()	Splits a string into an array of substrings \r\n
startsWith()	Checks whether a string begins with specified characters \r\n
substr()	Extracts a number of characters from a string, from a start index (position) \r\n
substring()	Extracts characters from a string, between two specified indices (positions) \r\n
toLocaleLowerCase()	Returns a string converted to lowercase letters, using the host's locale \r\n
toLocaleUpperCase()	Returns a string converted to uppercase letters, using the host's locale \r\n
toLowerCase()	Returns a string converted to lowercase letters \r\n
toString()	Returns a string or a string object as a string \r\n
toUpperCase()	Returns a string converted to uppercase letters \r\n
trim()	Returns a string with removed whitespaces \r\n
valueOf()	Returns the primitive value of a string or a string object \r\n

**String Properties** \r\n
constructor	Returns the string's constructor function \r\n
length	Returns the length of a string \r\n
prototype	Allows you to add properties and methods to an object \r\n

 
**JavaScript Numbers** \r\n
 
JavaScript has only one type of number. \r\n
let x = 3.14;     // A number with decimals \r\n
let y = 34;       // A number without decimals \r\n

**Numbers Methods**
Syntax \r\n
number.isFinite(); \r\n

isFinite()	Checks whether a value is a finite number \r\n
isInteger()	Checks whether a value is an integer \r\n
isNaN()	Checks whether a value is Number.NaN \r\n
isSafeInteger()	Checks whether a value is a safe integer \r\n
toExponential(x)	Converts a number into an exponential notation \r\n
toFixed(x)	Formats a number with x numbers of digits after the decimal point \r\n
toLocaleString()	Converts a number into a string, based on the locale settings \r\n
toPrecision(x)	Formats a number to x length \r\n
toString()	Converts a number to a string \r\n
valueOf()	Returns the primitive value of a number \r\n


**Numbers Properties**
Syntax \r\n
number.constructor; \r\n

constructor	Returns the function that created JavaScript's Number prototype \r\n
MAX_VALUE	Returns the largest number possible in JavaScript \r\n
MIN_VALUE	Returns the smallest number possible in JavaScript \r\n
NEGATIVE_INFINITY	Represents negative infinity (returned on overflow) \r\n
NaN	Represents a "Not-a-Number" value \r\n
POSITIVE_INFINITY	Represents infinity (returned on overflow) \r\n
prototype	Allows you to add properties and methods to an object \r\n

**JavaScript Booleans** \r\n
JavaScript booleans can have one of two values: true or false. \r\n

**JavaScript Boolean Methods** \r\n

toString()	Converts a boolean value to a string, and returns the result \r\n
valueOf()	Returns the primitive value of a boolean \r\n

**JavaScript Boolean Properties** \r\n

constructor	Returns the function that created JavaScript's Boolean prototype \r\n
prototype	Allows you to add properties and methods to the Boolean prototype \r\n



