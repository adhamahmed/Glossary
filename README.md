# Glossary

### P1 Provide a definition of what an algorithm is and outline the process in building an application

An algorithm is a step by step process to accomplish a task. It is a well-defined procedure or formula which allows a computer to solve a problem, based on conducting a sequence of specified actions. Within programming, it has a start, a middle, and an end. It is often written as pseudocode, such as a flowchart.

When building an application, the process usually follows a lifecycle model, such as the Waterfall Model which follows the steps:
- Identifying the basic requirements of the application from the client, which will dictate the rest of the development
- Create designs and plan the rest of the project, such as how the requirements will be met and implemented
- Once the outline has been created the language and IDE is chosen to best fit the team working on the programming
- Designs are handed to programmers to create the prototypes, mainly focused on the requirements
- Prototypes are then tested by a focus group, making sure the code works correctly and ensure stability of the application
- The application is continually maintained until possible release, such as bug fixing and updating to keep up to date


### M1 Determine the steps taken from writing code to execution

Execution process:

Step 1: Write Source Code(s)

Step 2: Preprocess

Step 3: Compile

Step 4: Link Edit

Step 5: Load

Step 6: Execute

Steps 2, 3, and 4 are all part of the build process, and steps 5 and 6 are part of the run process.

### P2 Give explanations of what procedural, object orientated and event driven paradigms are; their characteristics and the relationship between them

#### Procedural paradigm
The procedural programming paradigm is concerned with defining a linear procedure or sequence of programming statements. A key feature of the paradigm is the partitioning of functionality into small reusable modules called procedures, that act like small programs themselves with their own scope, inputs and outputs.

#### Object orientated paradigm
The object orientated programming paradigm is concerned with modeling problems in terms of entities called objects that have attributes and behaviors and interact with other entities using message passing (calling methods on other entities).

#### Event driven paradigm
Event driven programming is a programming paradigm in which the flow of program execution is determined by events. An event-driven application is designed to detect events as they occur, and then deal with them using an appropriate event handling procedure. Many visual programming environments will even provide code templates for event-handlers, so the programmer only needs to provide the code that defines the action the program should take when the event occurs. Each event-handler is usually bound to a specific object or control on a form. Any additional subroutines, methods, or function procedures required are usually placed in a separate code module, and can be called from other parts of the program as and when needed.

#### Relationship between paradigms
These paradigms have both similarities and differences which can be found in each other, which can be explained as they have been created one after another in order to solve different problems and keep up with the technology of the time.

Before the arrival of object orientated programming languages, event handlers would have been implemented as subroutines within a procedural program. The flow of program execution was determined by the programmer, and controlled from within the application’s main routine. The complexity of the logic involved required the implementation of a highly structured program. All of the program’s code would be written by the programmer, including the code required to ensure that events and exceptions were handled, as well as the code required to manage the flow of program execution.

Object orientated programming is different to the other two paradigms, as this takes a different approach to the implementation of the code. Instead of writing the code in a logical order or based on inputs, the class is used as a blueprint and the object can take some or all of the behaviours to create different objects.


### M2 Analyse the common features that a developer has access to in an IDE


### P4 Explain the debugging process and explain the debugging facilities available in the IDE

Debugging is the process of finding and resolving issues within parts of code. It involves a few steps: identifying the cause, determine a solution, and then testing to see if the solution works as intended.

With many IDEs, identifying the bug can be quite simple as it will point you to the line of code that causes the bug. Howevever, without the use of an IDE this part can be a rather difficult if you do not know what you are looking for.
The next step of coming up with a solution is up to the skills of the programmer without an IDE, as if you do not realise what is causing the bug it becomes quite hard to fix it. However, debugging facilities within IDEs are strong enough to help suggest what could be wrong, such as underlining a part of the code that needs fixing.
Testing solutions is as simple as running the code again. With the use of an IDE such as repl.it, the bug will show instantly in red text if there is one. If another bug or the same bug appears, the process starts again.

For the IDE repl.it, there is also a step debugging panel that allows you to step through each part of your code to allow you to go through it all while the code is running.


### M4 Evaluate how the debugging process can be used to help develop more secure, robust applications


### D3 Evaluate the use of an IDE for development of applications contrasted with not using an IDE


### D4 Critically evaluate why a coding standard is necessary in a team as well as for the individual

