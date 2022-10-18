# Class 7 Notes

- Control flow
  - The control flow is the order in which the computer executes statements in a script.

  - Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) 
    structures that change the control flow, such as conditionals and loops.

  - For example, imagine a script used to validate user data from a webpage form. 
    The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in.

- JavaScript Functions
  - A JavaScript function is a block of code designed to perform a particular task.

    A JavaScript function is executed when "something" invokes it (calls it).

- JavaScript Function Syntax
  - A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

  - Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

  - The parentheses may include parameter names separated by commas:
    (parameter1, parameter2, ...)

  - The code to be executed, by the function, is placed inside curly brackets: {}

- Function Invocation
  - The code inside the function will execute when "something" invokes (calls) the function:

    - When an event occurs (when a user clicks a button)
    - When it is invoked (called) from JavaScript code
    - Automatically (self invoked)

- Function Return
  - When JavaScript reaches a return statement, the function will stop executing.

  - If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

  - Functions often compute a return value.

- JavaScript Operators
  - The assignment operator (=) assigns a value to a variable.
  - The addition operator (+) adds numbers.
  - The multiplication operator (*) multiplies numbers.

- JavaScript Arithmetic Operators
  - Arithmetic operators are used to perform arithmetic on numbers:

     Operator	Description
     	(+) 		Addition
	(-)             Subtraction
	(*)		Multiplication
	(**)		Exponentiation (ES2016)
	(/)		Division
	(%)		Modulus (Division Remainder)
	(++)		Increment
	(--)		Decrement
