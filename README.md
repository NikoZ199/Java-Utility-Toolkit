# ezutils

The idea is to make coding projects faster and easier.
By making these small but powerful utilities once, you can reuse them in later projects.
The features of the toolkit are listed below.

## Utils Toolkit Plans
- local and remote database management
- filesystem management
- commandline argument handling
- configuration creator, serializer, and deserializer
- console handling
- task creation, checking, and management
- data transfer server and client with common internet protocols
- any other ease of use classes

## General Principles
- all code should be formatted using standard formatting
- only classes and methods that are meant to be accessed from outside the package should be public
- no other class but the Console class may print to the console, exceptions can apply
- code should be easy to read and fool proof, check all input
- organize all classes well, try categorize things into their own packages, no enormous spaghetti code
- if a class or more classes use a certain code to complete a task, you may create an assisting class
- all code must be able to compile, obviously
- use only the ONE testing class to test how your code behaves
- The Util class will combine all the sub-classes, from where they will be available for use
