# Readings : Debugging
## From the Duckett JS book:

- [JavaScript book, Ch. 10, “Error Handling & Debugging](https://drive.google.com/file/d/1L74jU_Js5jSjbi2hg87TNyT-hnVkoXwJ/view)

### Error Handling & Debugging

- *EXECUT.ION CONTEXTS*

There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.


- *EXECUTION CONTEXT& HOISTING*

 there are two phases of activity:

 - 1: PREPARE
 - 2: EXECUTE


 - If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code.


- In the interpreter, each execution context has its own va ri ables object.
   - It holds the variables, functions, and parameters available within it.
     - Each execution context can also access its parent's v a ri ables object.



- Error objects can help you find where your mistakes are
and browsers have tools to help you read them.



|OBJECT|DESCRIPTION|
|------|-----------|
|Error |Generic error - the other errors are all based upon this error|
|Syntax Error|Syntax has not been followed|
|Ref erenceError|Tried to reference a variable that is not declared/within scope|
|TypeError|An unexpected data type that cannot be coerced|
|Range Error|Numbers not in acceptable range|
|URI Error|encodeURI ().decodeURI(),and similar methods used incorrectly|
|EvalEr r or|eva l () function used incorrectly|




- Type Error
  - VALUE IS UNEXPECTED DATA TYPE
    - This is often caused by trying to use an object or method that does not exist.

- RangeError
  - NUMBER OUTSIDE OF RANGE
    - If you call a function using numbers outside of its accepted range.


- HOW TO DEAL WITH ERRORS
1.  DEBUG THE SCRIPT TO FIX ERRORS
2. 2: HANDLE ERRORS GRACEFULLY



**Debugging is about deduction: eliminating potential causes of an error.**


*The JavaScript console is just one of several developer tools that are found in all modern browsers.*

- HOW TO LOOK AT ERRORS IN CHROME:

*The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.*


- *TYPING IN THE CONSOLE IN CHROME*

You can also just type code into the console and it will show you a result.

- Browsers that have a console have a console object, which has several methods that your script can use to display data in the console. The object is documented in the Console API.


**The console helps narrow down the area in which the error is located, so you can try to find the exact error.**

- CONDITIONAL BREAKPOINTS

You can indicate that a breakpoint should ben triggered only if a condition that you specify is met. The condition can use existing variables.



- HANDLING EXCEPTIONS

If you know your code might fail, use try, catch, and finally. Each one is given its own code block.


- If you know something might cause a problem for your script, you can
generate your own errors before the interpreter creates them.


**Here are a selection of practical tips that you can try to use when debugging your scripts.**
- ANOTHER BROWSER
- ADD NUMBERS
- STRIP IT BACK
- EXPLAINING THE CODE
- SEARCH
- 