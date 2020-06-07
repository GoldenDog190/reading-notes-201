# Ducket - HTML & CSS / JavaScript & JQuery Notes

## JS Ch 10 "Error Handling & Debugging"
**Order of Execution**
- to find the source of the error, it helps to know how scripts are processed, and the order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
- *order of execution*: the order in which statements are processed
- JS interpreter uses of the concept of *execution context*. 
- *Execution context* every statement in a script lives in one of three execution context: global context, function context, and eval context
- *Variable scope*: the first two execution contexts correspond  with the notion of scope: global scope & function-level scope

**The Stack**
- The JS interpreter processes one line of codeat a time. When a statement needs data from another function, it stacks the new function on top of the current task

**Executing Context & Hoisting**
- Each time a script enters a new execution context, two phases of activity: 
  1. prepare 
  2. execute
- *Hoisting*: call fuctions before they have been declared, and assign a value to a variable that has not yet been declared

**Understanding the Scope**
- In the interpreter, each execution context has its own variables object, and it holds the variables, functions,  and parameters available within it.  Each execution context can also access its parent's variables object.
- *Lexical scope*: functions are linked to the object they were defined within.

**Understanding Errors**
- If JS statement generates an error, then it throws an exception