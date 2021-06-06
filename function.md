 
 
 **function in JavaScript**
 
  is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output


 ** JavaScript Function Syntax **

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}


Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

A Function is much the same as a Procedure or a Subroutine, in other programming languages

**Function Invocation **

The code inside the function will execute when "something" invokes (calls) the function:

* When an event occurs (when a user clicks a button)
* When it is invoked (called) from JavaScript code
* Automatically (self invoked)


**Function Return**

When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller"

![img](https://miro.medium.com/max/3762/1*aTDSVSNaaNVDAbuS6CjLMQ.png)


** Why Functions? **

You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

** The () Operator Invokes the Function **

Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.

Accessing a function without () will return the function object instead of the function result.

![img](https://cdn.programiz.com/cdn/farfuture/oAZVf3IqOKOYj_aJ-IoYQvbJ2CB-B3y4HXSLXBUmYcY/mtime:1591592163/sites/tutorial2program/files/javascript-function-with-parameter.png)

** Functions Used as Variable Values**

Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations

![img](https://i.stack.imgur.com/lcPvN.png)

** Local Variables**

Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.

![img](https://media.geeksforgeeks.org/wp-content/uploads/20190626103208/Screenshot-3471.png)

