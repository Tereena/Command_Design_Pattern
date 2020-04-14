# Command_Design_Pattern in c#
Command Design Pattern:

Command is behavioral design pattern that converts requests or simple operations into objects.

UML Diagram
The UML class diagram for the implementation of the command design pattern is given below:


Invoker  --> Asks the command to carry out the action
Command --> This is an interface which specifies the execute operation
Concrete Command --> Class that implements the execute operation by invoking on the receiver
Receiver class --> Class that performs the Action Associated with the Request

Command Pattern Example

The classes, interfaces, and objects in the above class diagram can be identified as follows:
Switch- Invoker class.
ICommand - Command interface.
FlipUpCommand and FlipDownCommand - Concrete Command classes.
Light - Receiver class.
