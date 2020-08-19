# Reading Notes for Class 10
  ## Chapter 10 Error Handling & Debugging

  **When writing a long series of code, nobody gets everything right the first attempt. The error messages that a browser gives may look foreign but the can help you to determine what went wrong within your script and how you can fix it. This Reading notes will cover:**
     *The console & DEV Tools* - Tools that are built into the browser that help hunt for errors.
     *Common problems* - Common sources of errors, and how to fix them.
     *Handling Errors* - How code can deal with potential errors gracefully. 

### Order of Execution

- To find the source of an error, It helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

### Execution contexts

- The JavaScript interpreter uses the concept of **Execution contexts**. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.
  - Every statement in a script lives in one of these three **execution contexts**:
    - ``Global Context`` - is code that is in the script, but not in a function. There is only one *Global Context* in any page.
    - ``Function Context`` - Code that is being run within a function. Each function has it's own *function context*.
    - ``Eval Context`` - Text is executed like code in an internal function called *eval(\)\

  - **Variable Scope** The first two execution contexts correspond with the notion of scope.
    - ``Global Scope`` - If a variable is declared outside a function, it can be used anywhere because it has *Global Scope*. If you do not use the **var** keyword when creating a variable, It is placed in *Global Scope*.
    - ``Function-Level Scope`` - When a variable is declared within a function, It can only be used within that function. This is because it has *Function-level Scope*.

### The Stack

- The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it **Stacks** the new function on top of the current task.

### Execution Context & Hoisting

- Each time a script enters a new **execution context**, there are two phases of activity:
  - Prepare;
    - The new scope is created.
    - Variables, Functions, and arguments are created.

  - Execute;
    - Now it can assign values to variables.
    - Reference functions and run their code.
    - Execute statements.

- Understanding how these two phases happen will help with understanding a concept called **hoisting**.
  - Call functions *before* the have been declared.
  - Assign a value to a variable that has not yet been declared.

### Understanding Scope

- In the Interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

### Understanding Errors

- If a JavaScript statement generates an error, then it throws an *exception.* At that point, the interpreter stops and looks for exception-handling code.

### Error Objects

- **Error Objects** can help you find where your mistakes are and browsers have tools to help you read them.

``SyntaxError`` - Syntax is not correct. Is Caused by incorrect use of the rules of the language. It's often the result of a typo.

``ReferenceError`` - Variable does not exist. This is caused by a variable that is not declared or is out of scope.

``TypeError`` - Value is unexpected data type. This is often caused by trying to use an object or method that does not exist.

``RangeError`` - Number outside of range. If you call a function using numbers outside of it's accepted range.

``URIError`` - Incorrect use of URI functions. If these characters are not escaped in URI's they will cause an error : /, ?, &, #, :, ;.

``NaN`` - Not an Error. If you perform a mathematical operation using a value that is not a number, you end up with the value of NaN, not a type error.

### How to deal with erors

- There are 2 things you can do with Errors :
    - **Debug the Script to fix Errors** 
    - **Handle Errors Gracefully**

### A Debugging Workflow

- Debbuging is about deduction: Elimination potential causes of an error.
  - Where is the problem ?
  - What exactly is the problem ? 

### Browser DEV tools & JavaScript Console

- The JavaScript Console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

- All modern browsers have some kind of Console that is aviable to use.

- When debugging errors it can help to look at the error in more than one browser as they can show you different errors.

- Browsers that have a console have a console object, which has several methods that your script can use to display data in the console. The object is documented in the console API. 

``Console.log`` - is a method that can write data from the script to the console. It also helps you check that your getting the values that you would expect to see.

- To differentiate between the types of messages you write to the console, you can use three different methods.
  - ``console.info()`` - can be used to generate general information.
  
  - ``console.warn()`` - Can be used for warnings.

  - ``console.error()`` - Can be used to hold errors.

### Writting Tabular Data

- In browsers that support it, the ``console.table()`` method lets yu output a table showing :
    - **Objects**
    - **Arrays that contain other objects or arrays**

### Writting on a condition 

- Using the ``console.assert()`` method, you can test if a condition is met, and write to the console only if the expression evaluates to false. 

### Breakpoints

- You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.

### Stepping through Code

- If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.

### Conditional Breakpoints

- You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables.

### Debugger Keyword

- You can create a breakpoint in your code using just the **Debugger Keyword**. When the developer tools are open, This will automatically create a breakpoint.

### Handling Exceptions

- If you know your code might fail, use **Try, Catch and Finally**. Each one is given it's own code block.
  - **Try** - first you specify the code that you think might throw an exception within the try block.
  - **Catch** - If the try code block throws an exception, catch steps in with an alternative set of code.
  - **Finally** - The contents of the finally code block will run either way- whether the try block succeeded or failed.




  [Return to the table of Contents](README.md)


