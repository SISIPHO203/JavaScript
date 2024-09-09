# JavaScript


Variable- it is a container that hold data values.
it allows you to store,update and manipulate information throughout your code.

 #Declaring variables.
var: has function scope and can be redeclared
let: has block scope and can be reassigned but not redeclared within the same scope.
const: has block scope and cannot be reasigned or redeclared which makes it ideal for values that should not change

#DATATYPES
Data types: type of data a variable can hold
Numbers:used for numeric values
Strings:used for text
Booleans: represent true/false , typically used in conditions and logical operations
Arrays: list of values which can be of any data type ,stored in a single variable.
Objects: complex data structures that can hold multiple values and functions (methods) as properties


#OPERATORS
operators are symbls or keywords used to perfom operations on values.

#TYPES OF OPERATIONS

Arithmetic operators: they are used for mathematical calculations(+addition,subraction-,multiplication*,devision/,exponentiation**,modulus%)
 
Assignment operators: they are used to assign values(=assign, +=add and assign,-=subract and assign, *=multiply and assign, /=divide and assign)

Comparison operators: they are used to compare values and return a boolean(true/false)
(==equal, !=not equal, ===strict equal, !==strict not equal, >greater than, <less than, >=greater than or equal to, <=less than or equal to)

Logical operators: they are used to combine multiple conditions(&& AND, || OR, ! NOT)

Unary operators: operate on a single operand(++increment, --decrement,typeof type of operand)

Ternary operator: shorthand for and if-else statement

#EXPRESSIONS

Arithmetic expressions:they are used to perfom calculations
let total price = price*quantity;

Comparison expressions: they are used to evaluate conditions
let isAdult = age >= 18;

Logical expresions:they are used to combine multiple conditions
let canVote =(age >=18) && (citizen ===true)

#if-else Statements:

it is a fundamental control structure that executes a block code if a specified condition is true, if the condition is false the else block is executed instead.

if Block: executes when condition is true.

else if Block : optional checks another condition if the previous one was false.
else Block: executes when none of the previous condition are met.


#switch Statements

switch statement is another control structure used for executing one block of code among many based on the value of an expression.


switch keyword: evaluates an expression and matches it to one of several case labels.

case labels: each case contains the code to execute if the expression matches the label.

break statement: stops the execution of more cases after a match is found, without break the code will continue executing the subsequent cases.

default case: executes if no matching case is found, it's optional but often used as fallback.
 
Switch statement  is ideal when you need to compare a single expression against multiple potential values.



#FUNCTIONS


a function is a reusable block of code designed to perfom a specific task.Functions allows developers to write code once and use it multiple times, which enhances code efficiency and readability.

Function declaration: it can be declared using the function keyword followed by name , alist of parameters(optional) and a block of code.

Parameters and Arguments: functions can take parameters -values that are passed into the function when it is called, these parameters are used within the function to perfom operations .The actual values passed to the function are called arguments


Retiurn value : a function can return a value using the return statement.

Calling functions: to execute the code within a function you call the function by it's name ,folowed by paranthesis,optionally passing in arguments.



#SCOPE
 

scope dertemines the accesibility of variables and functions in different parts of the code.

Global scope: variables declared outside of any function or block have global scope and can be accesed from anywhere in the code

Local scope: variables declared within a function or block are local to that function or block and cannot be accesed from outside it

Function scope: variables declared within a function are accesible only within that function.

Block scope: variables declared with let or const within a block({}) are accesible only within that block.


#DOM (DOCUMENT OBJECT MODEL)

DOM is a structured representation of an HTML document, it represents the page so that programs can change the document structure ,style and content.

#SELECTING DOMs
targeting specific parts of the HTML document so that they can be manipulated with JavaScript

Methods for selecting elements

getElementById: selects a single element by its unique id.
getElementByClassName: selects all elements that share the same class name.
getElementByTagName: selects all elements with specific a tag name.
querySelector: selects the first element that matches a specified a CSS selector.
querySelectorAll:selects all elemntys that match a specified CSS selector


#MODIFYING DOM ELEMENTS
Once elements are selected they can be modified in various ways, such as changing their content,style,attributes or structure

Common modifications

Changing content: use the textContent or innerHTML properties to update the text or HTML inside an element.
Changing styles: use the style proprty to modify the CSS style of an element(e. element.style.color="blue";).
Adding/removing classes: use classlist.add, classlist.remove or classlist.toggle to manipulate an element's classes.
Changin Attributes: use setAttribute and removeAttribute to modify or rmove attributes like src,href,alt etc.










 








