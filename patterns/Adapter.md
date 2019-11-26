# Adapter

Convert the interface of a class into another interface that the clients expect.
Adapater lets classes work together that could not otherwise because of incompatible interfaces.

| Questions | Facade | Adapter |
| ---- | ---- | ----|
|Are there preexisting classes ？ | Yes | Yes|
|Is there an interface we must design to ? | No | Yes|
| Does an object need to behave polymorphically ? | No | Probably |
| Is a simpler interface needed ? | Yes |No |

 * In both the Facade and Adapter pattern I have preexisting classes
 * In the Facade, however, I do not have an interface I must design to, as I do in the Adapter pattern.
 * I am not interested in polymorphic behavior in the Facade, while in the Adapter, I probably am. 
 * In the case of the Facade pattern, the motivation is to simplify the interface. With the Adapter, while simpler is better, I am trying to design to an existing  interface and cannot simplfy things even if a simpler interface were otherwise possible.
 
 # A Facade simplifies an interface while an Adapter converts the interface into a preexisting interface
 
 
