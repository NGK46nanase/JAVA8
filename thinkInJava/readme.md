#Interface
* To upcast to more than one base type ( and the flexibility that this provides).
* To prevent the client programmer from making an object of this class and to establish that it is only an interface.

Normally, you can use __extends__ with only a single class, but __extends__ can refer to multiple base interfaces when building a new 
interface. 

# Inner Class

If you want to make an object of the inner class anywhere except from within a __non-static__ method of the outer clas, you must specify the type of that object as _OuterClassName.InnerClassName_ 


Normal (non-inner) class cannot be made private or protectedl they may only be given __public__ or package access.

