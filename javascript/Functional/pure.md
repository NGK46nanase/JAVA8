Pure functions: use functions that avoid side effects and changes of state
 * It depends only on the input provided and not on any hidden or external state that may change during its evaluation or between calls
 * It doesn't inflict changes beyond their scope, such as modifying a global object or a parameter passed by reference.
 
 
 Side effects:
  - Changing a variable, property, or data structure globally
  - Changing the original value of a function's argument
  - Processing user input
  - Throwing an exception, unless it's caught within the same function
  - Printing to the screen or logging
  - Querying the HTML documents, browser cookies, or database
 
 
 
