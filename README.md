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

## Useful sources

- If something doesn't work, you can always search for old solutions on [Stack Overflow][]
- Optionally you can also always search the [Internet][]
- Learn more about [Gradle][], it may be [important][]
- The latest information about this project is obviously on the [Github][] page
- For documentation of Java you may use [Java 8 Docs API][] or [DevDocs][]
- If you're wondering, this document is made in [Markdown][]

[//]: # (References)
[Stack Overflow]: https://stackoverflow.com/
[Gradle]: https://docs.gradle.org/current/userguide/userguide.html
[Java 8 Docs API]: https://docs.oracle.com/javase/8/docs/api/
[Github]: https://github.com/NikoZ199/Java-Utility-Toolkit
[DevDocs]: https://devdocs.io/openjdk~8/
[Markdown]: https://daringfireball.net/projects/markdown/
[important]: https://www.youtube.com/embed/IwLSrNu1ppI?autoplay=true
[Internet]: http://bfy.tw/8uwE
