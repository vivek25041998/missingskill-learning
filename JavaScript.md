# History Of JavaScript
In 1995 javascript was created by Netscape devloper name Breandan Eich.first it was called Mocha.later it was renamed livescript.later Netscape change the name livescript to javascript.first version of javascript was 1.0. at that time miscrosoft introduce internet explorer which has its own version of javascript called jscript.at a time market has two different versions of javascript.later netscape give the proposal to ECMA to combined whith her and launched the javasript 1.1.which knows as ECDAscript or ek ma script.
## JavaScript:
javascript is design to interact with element of web pages in browser
# Variable
javascript is a dynamically type language.variable are container that store data.
- var:
  - it can be redeclare
  - it can be reinitilized
  - it can be get hoisted
  - functional scope
  - ES5 
- let
  - it can not redeclare
  - it can be reinitilized
  - it can not get hoisted 
  - laxical scope
  - ES6
- const
  - it can not redeclared
  - it can not reinitilized
  - it can not get hoisted
  - laxical scope 
  - ES6
# Control Structure
- if else:
- for:
- switch: (better way available in JS)
- while: (Normal use)
- do while: (Normal use)
# Operators
- Airthmatics: +,-,*,/,%,++,--,>=,<=,==,===
- Logical:&&,||,!
- Bitwise:<<,>>,!
- Relational: <,>,+=
- Trenary: ?,:
### Airthmatic Operator
- + : it is use for add and concat both.
- == : it is only check value of number not datatype
### Logical Operator
- && : evaluated untill truthy value true and stop when falsy value false is encountred
  - true && false = false
  - false && false = false
  - false && true = false
  - true && true = true
- || : evaluated untill falsy value false and stop when truthy value true is encountred
  - true || true = true
  - true || false = true
  - false || true = true
  - false || false = false 
# Scope
- functiional scope: each program can be called as functional scope.each program have their own functional scope
  - Global scope : these are define outside of function
  - local scope : these are define inside function
- Lacxical/block scope: start and end with curly bracket ({}). 
# Data Type
- primitive : these are pass or copy by value.it contain single type value
  - string: it is enclose with queats.
  - number
  -  boolean : two value true or false
  -  undefined : value is not assign
  -  null : it has nothing
- non primitive : these are pass or copy by refrence.it can cantain multiple value
  - object : key value pair
  - array : value,value
# Arrays
- arrays are special type of object.
- some array have diffrent type of value.
#### Ways To Declare Array 
var a = [1,2,3,4]
#### Length Of Array : length of array is last index + 1
#### .forEach() : loop over every element in arrayand does not return undefined
#### .filter() : iterats all item based on condition and return same length or less
#### .map() : return new array of same length
## Object
- it has key value pair
- object literal most used
- it uses bracket notation
## Object Static Methods
- object.keyt() : return array with all key of object
- object.values() : return array with all the value of object.
- object.assign() : create copy of all primitive but non primitive are still pass by reference
# Function 
- in javascript everything is an object.function are also an object.
- anything in function that can be access only whithin a function
## Two Ways For Declaring A Function
1. function declaration : always start with function keyword,define a function with a name
2. function assignment: assignment doen not hoisted varible declaration get hoisted.
- function are first class citizen.it can do anything
  - it can be object
  - can be value in array
### Higher Order Function
- function take function as parameter and return function.
### Pure Function
- we do not update value of input parameter within a function.
### Function Short Circuit
- whenever function return a function we can invoke the return function using () within assign to variable.
### Nested Function
- function within function is know ans nested function.
### Inline Function
- if we do not want to expose function expression and anonimous funtion then we use inline function.
### ES6-Arrow Function
- it does not have its own context
- function assignment does not get hoisted.
## Built-In Function
### Timer Function
- setTimeout() : delay code by given time.
### Parse Method
- convert string to number primitive type and return it.
## JSON Built-In Object
- object as data us whithin program
### JSON Method
- .stringify({}) : convrt object to json string,used when we want to send outside data
- .parse() : convrt json to object string,used when we get data from outside
