 
 public method  ( of an object) : get their object context from _this_

when a function is not the property of an object, then it is invoked as a function. _this_ is bound to the global object.

tail recursion optimization , if a function returns the result of invoking itself recursively, then the invocation is replaced with
a loop, which can significantly speed things up.   !!! Javascript does not suppot tail recursion optimization !!!

function scope, the parameters and variables defined in a function are not visible outside of the function, and that a variable defined anywhere within a function is visible everywhere within the function.

