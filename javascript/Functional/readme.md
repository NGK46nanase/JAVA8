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
 


Object-oriented design focuses on the nature of data and data relationships

functional programming focuses on the operations performed-behavior


|----|Funciontal|Object-oriented|
|-----|-----|-----|
|Unit of composition|Functions | Objects(classes) |
|Programming style|Declarative | Imperatives |
|Data and behavior|Loosely coupled into pure, standalone functions | Tightly coupled in classes with methods|
|State management|Treats objects as immutable values | Favors mutation of objects via instance methods |
|Control flow |Functions and recursion | Loops and conditions |
|Thread safety|Enables concurrent programming | Difficult to achieve |
|Encapsulation |Not needed because everything is immutable |Needed to protect data integrity |
 
 
