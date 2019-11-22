Both creates an object and isolates a client from knowing which class to instantiate.

In FACTORY METHOD, you will find several classes that implement the same operation, returning the same
abstract type but internally instantiating different classes that implement the type.

When a client requests a new object, the precise class of the object that is created depends on the 
behavior of the factory object receiving the creation request

defer the decision of which class to instantiate
