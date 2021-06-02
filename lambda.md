lambda in the the context of a function interface 

#functional interface# 

````
public interface Predicate<T> {
  boolean test (T t);
}
````


a functional interface is an interface that specifies exactly one abstract method. 

An interface is still a functional interface if it has many default methods as long as it specifies only one abstract method.

such as Compartor and Runnable 



Lambda expressions let you provide the implementation of the abstract method of a functional interface directly inline and treat the whole 
expression as an instance of a functional interface ( an instance of a concrete implementation of the functional interface). 


#function descriptor#
the signature of the abstract method of the functional interface descrive the signature of the lambda expression. 

lambda expression can e assigned to 
 *  a variable
 *  a method expecting a funcional interface as argument (the lambda expression has the same signature as the abstract method of the functional interface)

## Predicate<T> ##   
  accepts an object of generic type T and returns a boolean

  
## Consumer<T>
  takes an object of generic type T and returns no result (void) 
  
  
## Function<T,R> 
  takes an object of generic type T as input and returns an object of type R. such as maps information from an input object to an output 
  
the type of a lambda is deduced from the context in which the lambda is used. 
the type expected for the lambda expression inside the context is called the target type.
  
  If a lambda has a statement expression as its body, it's compatible with a function descriptor that return void. 
  
  ### Type Inference 
  The Java compiler deduces what functional inteface to associate with a lambda expression from its surroinding context (the target type).
  
  ### Using local variables
 lambda expressions are allowed to user free variables like anonymous classes can. But 
  * local variables to be explicitly declared final or be effectively final
  * be assigned to only once 
  
  Question :  lambda expression , thread, memory leak 
  Hint:  *  instance variable  stored on the head. local variable on the stack.  what if the thread using the lambda could try to access the variable after
  the thread that allocated the variable has deallocated it  * clousure
  
  #Method Reference 
  
  If a lambda represents "call this method directly,"  it's best to refer to the method by name rather than by a description of how to call it. 
  
  When you need a method reference , 
  
  target reference :: the name of the method 
  
  
  |---- Kind ----|---- Syntax----|---- Examples----|
  |Reference to a static method |  ContainingClass::staticMethodName | Person::compareByAge or MethodReferencesExamples::appendStrings | 
  | Reference to an instance method of a particular object | containingObject::instanceMethodName | myApp::appendString2 or myComparisonProvide::compareByName |
  | Reference to an instance method of an arbitrary object of a particular type | ContainingType::methodName | String::contact or String::compartToIgnoreCase| 
  | Reference to a constructor | ClassName::new | HashSet::new |
  
  
  
  1. A method reference to a static method (for example, the method parseInt of Integer, written Integer:parseInt) 
  
  2. A method reference to an instance method of an arbitrary type (for example, the method length of a String, written String::length )  * referring to a method to an object that
  will be supplied as one of the parameters of the lambda.
  
  3. A method reference to an instance method of an existing object or expression ( for example, suppose you have a local variable expensiveTransaction that holds an
  object of type Transaction, which supports an instance method getValue;  you can wrtie expensiveTransaction::getValue ) * calling a method in a lambda to an external object that 
  alread exists. , particularly useful when you need to pass around a method defined as a private helper. 
  
  
  
  
