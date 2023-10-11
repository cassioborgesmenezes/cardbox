---
id: 202308081114
alias: 
tags: zettel/fleeting programming/cleancode pattern/design

created: 2023-08-08, 11:14
modified: 2023-08-08, 11:14
---
# Command Pattern
<!-- Main content of my thoughts really -->

- The Command pattern is a way of encapsulating all the information needed to perform an action or trigger an event in an object. This object can then be passed to another object that can execute the command without knowing the details of how it works. This allows for loose coupling and flexibility in a request-response model
- bing: Considering Java how can i use an executable parameter to a class
- It seems you want to pass an executable block as a parameter to a class in Java. One way to do that is to use an interface that defines a method to execute the block, and then pass an object of a class that implements that interface. This is known as the Command pattern. Another way is to use a lambda expression or a method reference that can be assigned to a functional interface. You can also pass parameters to a jar file at the time of execution by using the -jar option and specifying the arguments after the jar file name
- Sure, here is one example of the Command pattern in Java:
	- Create a Command interface that defines a method to execute the command.
	- Create a Receiver class that contains the logic to perform the action or event.
	- Create concrete classes that implement the Command interface and include a Receiver object instance with appropriate arguments to perform the concrete execution.
	- Create an Invoker class that can take and execute commands.
	- Create a Client class that can create and pass commands to the Invoker.
## Questões
<!-- What remains for you to consider? --> 

- 

## Referências
<!-- Links to pages not referenced in the content -->

- [Example](https://www.dineshonjava.com/command-pattern-design-patterns-java/)
