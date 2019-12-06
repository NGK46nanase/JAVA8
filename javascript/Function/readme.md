| | Functional | Object-Oriented|
|-----|----|----|
|Unit of composition |Functions  | Objects (classes) |
|Programming style | Declarartive| Imperative|
|Data and behavior |Loosely coupled into pure, standalone functions funcitons | Tighttly coupled in classes with methods |
|State management | Treats objects as immutable values | Favors mutation of objects via instnce methods |
|Control flow | Functions and recursion | Loops and conditionals |
|Thread safety| Enables concurrent programming  | Difficult to achive|
|Encapsulation | Not needed because everthing is immutable | Needed to protect data integrity|

#closures : functions are executed using the scope chain that was in effect when they were defined. __scope chain?__
 
 public method  ( of an object) : get their object context from _this_

when a function is not the property of an object, then it is invoked as a function. _this_ is bound to the global object.

tail recursion optimization , if a function returns the result of invoking itself recursively, then the invocation is replaced with
a loop, which can significantly speed things up.   !!! Javascript does not suppot tail recursion optimization !!!

function scope, the parameters and variables defined in a function are not visible outside of the function, and that a variable defined anywhere within a function is visible everywhere within the function.

# pseudoclassical pattern vs. differential pattern vs. functional pattern



If we create an object in the functional style, and if all of the methods of the object make no use of _this_ or _that_, then the object
is __durable__

A durable object is simply a collection of functions that act as _capabilities_.

_Purity_ in this sense refers to the existence of a pure mapping between a function's arguments and its return value.

_referentially transparent_ : a function consistenly yields the same result on the same input


# Functional programming : the declarative evaluation of pure functions to create immutable programs by avoiding externally 
observable side effects.
 - declarative
 - pure
 - immutable


