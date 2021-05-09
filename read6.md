# what i’ve learned
### JavaScript Functions
* A JavaScript function is a block of code designed to perform a particular task.

* A JavaScript function is executed when "something" invokes it (calls it).

#### JavaScript Function Syntax
- function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

#### Function Invocation
 followed by:

- [x] When an event occurs (when a user clicks a button)
- [x] When it is invoked (called) from JavaScript code
- [x] Automatically (self invoked)

#### Function Return
*When JavaScript reaches a return statement, the function will stop executing.* 

- Example

Calculate the product of two numbers, and return the result:

var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
The result in x will be:

12



### Why Functions?
- You can reuse code: Define the code once, and use it many times.

- You can use the same code many times with different arguments, to produce different results.

#### The () Operator Invokes the Function

- Example
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;


#### Functions Used as Variable Values
- unctions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

## Test Yourself With Exercises
[link](https://www.w3schools.com/js/exercise_js.asp?filename=exercise_js_functions1)


### [for more detials](https://www.w3schools.com/js/js_functions.asp)

 
## Defining functions
### Function declarations

 function square(number) {
  return number * number;
}
* Example

function myFunc(theObject) {
  theObject.make = 'Toyota';
}

var mycar = {make: 'Honda', model: 'Accord', year: 1998};
var x, y;

x = mycar.make; // x gets the value "Honda"

myFunc(mycar);
y = mycar.make; // y gets the value "Toyota"
                // (the make property was changed by the function)

###  Function expressions
- example

const square = function(number) { return number * number }
var x = square(4) // x gets the value 16

### Calling functions
*Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.*
[more detials](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).






