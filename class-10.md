# Error Handling and Debugging

## Order of Execution

- To find the source of an error, it helps to know how scripts are processed. 

- The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

## Execution Contexts

- The JavaScript interpreter uses the concept of execution contexts.

- There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope. 

### Execution Context

- `GLOBAL CONTEXT` - Code that is in the script, but not in a function. There is only one global context in any page. 

- `FUNCTION CONTEXT` - Code that is being run within a function. Each function has its own function context. 

- `EVAL CONTEXT` - 
Text is executed like code in an internal function called eva l {).

### Variable Scope

- `GLOBAL SCOPE` - If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 

- `FUNCTION-LEVEL SCOPE` - When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope. 

## The Stack

- The JS interpreter one line of code at at a time.

- When a statement needs data from another function, it stacks the new function on top of the ccurrent task.

## Understanding Scope

- In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it.

- Each execution context can also access its parent's v a ri ables object.

## Understanding Errors

- If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

## Error Objects

- Error objects can help you find where your mistakes are and browsers have tools to help you read them.

## How to deal with Errors

- Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 

- `Debug the script to fix errors` - If you come across an error while writing a script, you will need to debug the code, track down the source of the error, and fix it.

- `Handle errors gracefully` - You can handle errors gracefully using try, catch, throw, and finally statements. 

- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 

- The console helps narrow down the area in which the error is located, so you can try to find the exact error. 