# Class 8 Notes

- Assignment operators
 - An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 
 - That is, x = f() is an assignment expression that assigns the value of f() to x.

- Assigning to properties
 - If an expression evaluates to an object, then the left-hand side of 
   an assignment expression may make assignments to properties of that expression.

- Destructuring
 - For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects 
   using a syntax that mirrors the construction of array and object literals.

- Evaluation and nesting
 - In general, assignments are used within a variable declaration 
   (i.e., with const, let, or var) or as standalone statements).


- Comparison operators
 - A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. 
   Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. 
   This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. 
   These operators do not attempt to convert the operands to compatible types before checking equality.

- Loops
 - Loops offer a quick and easy way to do something repeatedly. 
   - This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.
   - You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.

 -There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)
  - The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more 
    easily served by one type of loop over the others.

 - for statement
   - A for loop repeats until a specified condition evaluates to false. 
     The JavaScript for loop is similar to the Java and C for loop.

   - JavaScript
    - Here, the for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the <select> element, performs the 
      succeeding if statement, and increments i by 1 after each pass through the loop.

 - while statement
    - A while statement executes its statements as long as a specified condition evaluates to true.

    - If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
      - The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, 
        execution stops, and control is passed to the statement following while.
