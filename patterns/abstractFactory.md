# Abstract Factory 

| Issue | Expanation | 
| ----  | ----       |
|Intent | You want to have families or sets of objects for particular clients (or cases )|
| Problem | Families of related objects need to be instantiated | 
| Solution | Coordinates the creation of families of objects. Gives a way to take the rules of how to perform the instantiation out of the client object that is using these created objects |
| Participants and Collaborators | The Abstract Factory defines the interface for how to create each member of the family of objects required. Typically, each family is created by having its own unique ConcreateFactory. |
| Consequences | The pattern isolates the rules of which objects to use from the logic how to use these objects | 
| Implementation | Define an abstract class that specifies which objects are to be made. Then implement one concrete class for each family. Tables or files can also be used to accomplish the same thing |

decomposition by responsibility

Using the Abstract Factory is inidicated when the problem domain has different families of objects present and 
each family is used under different circumstances.
