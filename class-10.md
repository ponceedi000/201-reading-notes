## Readings: Debugging
***
### Chapter 10: “Error Handling & Debugging” - From the Duckett JS book
- > "JavaScript can be hard to learn and everyone makes mistakes when writing it."
  * I really liked the way this chapter opens. When coding JavaScript, you're likely to make a mistake at some point and I'm excited to learn how to properly debug code efficiently!
- Finding the source of an error is easier to find if you are how the scripts are processed. This referred to knowing the "order of execution". "The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run." - Duckett
- > "The JavaScript interpreter uses the concept of **execution contexts**. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope" - Duckett
  * Execution Context: 
    * Global Context = Code that is in the script, but not in a function. There is only one global context in any page
    * Function Context = Code that is in the script, but not in a function. Each function has its own function context.
    * Eval Context =  Text is executed like code in an internal function called **eval()**.
- The Stack: "The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it **stacks** (or piles) the new function on top of the current task." - Duckett
- Error objects can help you find where your mistakes are, and browsers have tools to help you read them.
  * When an **Error** object is created, it will contain the following properties:
    * Property -> Description
    * name -> Type of an error
    * message -> Description
    * fileNumber ->  Name of the JavaScript file
    * lineNumber ->  Line number of error
    
  * There are seven types of built-in error objects in JavaScript:
    * Error ->  Generic error - the other errors are all based upon this error
    * SyntaxError ->  Syntax has not been followed
    * ReferenceError ->  Tried to reference a variable that is not declared/within scope
    * TypeError ->  An unexpected data type that cannot be coerced
    * RangeError ->  Numbers not in acceptable range
    * URIError ->  encodeURI (), decodeURI (), and similar methods used incorrectly
    * EvalError ->  eval() function used incorrectly
- Now that we know these common errors, we can understand how to deal with errors:
  * Debugging the script to fix errors:
    * > If you come across an error while writing a script, you will need to debug the code, track down the source of the error, and fix it.
    * You can use the developer tools available in every modern browser.
  * Handle errors gracefully:
    * > You can handle errors gracefully using try, catch, throw, and finally statements.
    * Occasionally, an error may appear in the script when it's completely out of your control... Like requesting data from a 3rd party and their servers may be down. This is where it is important to know how to write error-handling code.
- The rest of this chapter talks about more useful methods for debugging but the notes above cover the most important fundamentals.
***
 ## End of Notes

