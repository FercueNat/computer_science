# Computer Science

## Table of Contents
- [Introduction](#introduction)
- [Electronic Computing](#electronic-computing)
- [Boolean Logic](#boolean-logic)
- [Number Systems](#number-systems)
- [Registers and RAM](#registers-and-ram)
- [Central Processing Unit(CPU)](#central-processing-unitcpu)
- [Instruction and Program](#instruction-and-program)
- [Programming Language](#programming-language)
- [Data Types](#data-types)
- [Statements and Functions](#statement-and-function)
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)
- [Alan Turing](#alan-turing)
- [Software Engineering](#software-engineering)
- [Integrated Circuits](#integrated-circuits)
- [Operating Systems](#operating-systems)
- [Memory and Storage](#memory-and-storage)
- [File System](#file-system)

## Introduction
Computer science is the study of computers and computing as well as their theoretical and practical applications. Computer science applies the principles of mathematics, engineering, and logic to a plethora of functions, including algorithm formulation, software and hardware development, and artificial intelligence.

## [Electronic Computing](#electronic-computing)
A device that computes, especially a programmable electronic machine that performs high-speed mathematical or logical operations or that assembles, stores, correlates, or otherwise processes information.

## [Boolean Logic](Boolean%20Logic/readme.md)
Boolean logic is a branch of mathematics that deals with the values of truth and falsehood. It is a system of logic that uses only two values, 0 and 1, to represent false and true, respectively. It is also known as Boolean algebra, named after George Boole, who first described it in 1854.
### Common Boolean Operators
| Operator | Name | Description |
|:--------:|:----:|:-----------:|
| ! | NOT | Negates the value of the operand. |
| && | AND | Returns true if both operands are true. |
| \|\| | OR | Returns true if either operand is true. |

## [Number Systems](Number%20System/readme.md#number-systems)

Number systems are a mathematical system for expressing numbers. A number system consists of a set of symbols that are used to represent numbers, and a set of rules for manipulating those symbols. The symbols used in a number system are called numerals.

### [Types of Number Systems](#types-of-number-systems)

- [Positional Numeral System](Number%20System/readme.md#positional-numeral-system)
- [Sign-value Notation System](Number%20System/readme.md#sign-value-notation-system)

### [Common Positional Number Systems](#common-positional-number-systems)

- [Binary](Number%20System/readme.md#binary)
- [Octal](Number%20System/readme.md#octal)
- [Decimal](Number%20System/readme.md#decimal)
- [Hexadecimal](Number%20System/readme.md#hexadecimal)

## [Registers and RAM](#registers-and-ram)
Registers are small amounts of high-speed memory contained within the CPU. They are used by the processor to store small amounts of data that are needed during processing. Whereas RAM stands for random-access memory. It is essentially short term memory where data is stored as the processor needs it.

## [Central Processing Unit(CPU)](#central-processing-unit)
A central processing unit (CPU) is an important part of every computer. The CPU sends signals to control the other parts of the computer, almost like how a brain controls a body.
The CPU is an electronic machine that works on a list of computer things to do, called instructions. It reads the list of instructions and runs (executes) each one in order. A list of instructions that a CPU can run is a computer program.

## [Instruction and Program](#instruction-and-program)
In computer science, an instruction is a single operation of a processor defined by the processor instruction set. And a  computer program is a list of instructions that tell a computer what to do. Everything a computer does is done by using a computer program. Programs stored in the memory of a computer ("internal programming") let the computer do one thing after another, even with breaks in between.

## [Programming Language](#programming-language)
A programming language is any set of rules that converts strings, or graphical program elements in the case of visual programming languages, to various kinds of machine code output.[citation needed] Programming languages are one kind of computer language, and are used in computer programming to implement algorithms.

## [Data Types](#data-types)
A data type, in programming, is a classification that specifies which type of value a variable has and what type of mathematical, relational or logical operations can be applied to it without causing an error.

## [Data Structures](Data%20Structures/readme.md)
In computer science, a data structure is a data organization, management, and storage format that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.

### Types of Data Structures
- [Array](Data%20Structures/readme.md#array)
- [Linked List](Data%20Structures/readme.md#linkedlist)
- [Stack](Data%20Structures/readme.md#stack)
- [Queue](Data%20Structures/readme.md#queue)
- [Hash Table](Data%20Structures/readme.md#hashtable)
- [Heap](Data%20Structures/readme.md#heap)
- [Tree](Data%20Structures/readme.md#tree)
- [Graph](Data%20Structures/readme.md#graph)

## [Algorithms](Algorithms/readme.md)
Algorithms are the sets of steps necessary to complete computation - they are at the heart of what our devices actually do. And this isn’t a new concept. Since the development of math itself algorithms have been needed to help us complete tasks more efficiently, but today we’re going to take a look a couple modern computing problems like sorting and graph search, and show how we’ve made them more efficient so you can more easily find cheap airfare or map directions to Winterfell... or like a restaurant or something.

### [Sorting](Algorithms/Sorting/readme.md)
Sorting is the process of arranging a list of items in a particular order. For example, if you had a list of names, you might want to sort them alphabetically. Or if you had a list of numbers, you might want to put them in order from smallest to largest. Sorting is a common task, and it’s one that we can do in many different ways.

### [Graph Search](Algorithms/Graph%20Search/readme.md)
Graph search is the process of searching through a graph to find a particular node. A graph is a data structure that consists of a finite (and possibly mutable) set of vertices or nodes or points, together with a set of unordered pairs of these vertices for an undirected graph or a set of ordered pairs for a directed graph. These pairs are known as edges, arcs, or lines for an undirected graph and as arrows, directed edges, directed arcs, or directed lines for a directed graph. The vertices may be part of the graph structure, or may be external entities represented by integer indices or references. Graphs are one of the most useful data structures for many real-world applications. Graphs are used to model pairwise relations between objects. For example, the airline route network is a graph in which the cities are the vertices and the flight routes are the edges. Graphs are also used to represent networks. The Internet can be modeled as a graph in which the computers are the vertices and the links between computers are the edges. Graphs are also used in social networks like linkedIn, Facebook. In fact, graphs are used to represent many real-world applications: computer networks, circuit design, and aeronautical scheduling to name just a few.


### Dynamic Programming
Dynamic programming is both a mathematical optimization method and a computer programming method. The method was developed by Richard Bellman in the 1950s and has found applications in numerous fields, from aerospace engineering to economics. In both contexts it refers to simplifying a complicated problem by breaking it down into simpler sub-problems in a recursive manner. While some decision problems cannot be taken apart this way, decisions that span several points in time do often break apart recursively. Likewise, in computer science, if a problem can be solved optimally by breaking it into sub-problems and then recursively finding the optimal solutions to the sub-problems, then it is said to have optimal substructure. Dynamic programming is one way to solve problems with these properties. The process of breaking a complicated problem down into simpler sub-problems is called "divide and conquer".


### Greedy Algorithms
Greedy algorithms are a simple, intuitive class of algorithms that can be used to find the optimal solution to some optimization problems. They are called greedy because at each step they make the choice that seems best at that moment. This means that greedy algorithms do not guarantee to return the globally optimal solution, but instead make locally optimal choices in the hope of finding a global optimum. Greedy algorithms are used for optimization problems. An optimization problem can be solved using Greedy if the problem has the following property: at every step, we can make a choice that looks best at the moment, and we get the optimal solution of the complete problem.


### Backtracking
Backtracking is an algorithmic-technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time (by time, here, is referred to the time elapsed till reaching any level of the search tree).


### Branch and Bound
Branch and bound is a general technique for solving combinatorial optimization problems. It is a systematic enumeration technique that reduces the number of candidate solutions by using the problem's structure to eliminate candidate solutions that cannot possibly be optimal. It is a divide and conquer algorithm that is used to solve optimization problems. It is a systematic enumeration technique that reduces the number of candidate solutions by using the problem's structure to eliminate candidate solutions that cannot possibly be optimal. It is a divide and conquer algorithm that is used to solve optimization problems. It is a systematic enumeration technique that reduces the number of candidate solutions by using the problem's structure to eliminate candidate solutions that cannot possibly be optimal. It is a divide and conquer algorithm that is used to solve optimization problems.

## [Alan Turing](Alan%20Turing/readme.md)
Alan Turing, (born June 23, 1912, London, Eng.—died June 7, 1954, Wilmslow, Cheshire), English mathematician and logician. He studied at the University of Cambridge and at Princeton’s Institute for Advanced Study. In his seminal 1936 paper “On Computable Numbers,” he proved that there cannot exist any universal algorithmic method of determining truth in mathematics and that mathematics will always contain undecidable (as opposed to unknown) propositions. That paper also introduced the Turing machine. He believed that computers eventually would be capable of thought indistinguishable from that of a human and proposed a simple test (see Turing test) to assess this capability. His papers on the subject are widely acknowledged as the foundation of research in artificial intelligence. He did valuable work in cryptography during World War II, playing an important role in breaking the Enigma code used by Germany for radio communications. After the war he taught at the University of Manchester and began work on what is now known as artificial intelligence. In the midst of this groundbreaking work, Turing was found dead in his bed, poisoned by cyanide. His death followed his arrest for a homosexual act (then a crime) and sentence of 12 months of hormone “therapy.

Following a public campaign in 2009, the British Prime Minister Gordon Brown made an official public apology on behalf of the British government for "the appalling way [Turing] was treated". Queen Elizabeth II granted a posthumous pardon in 2013. The term "Alan Turing law" is now used informally to refer to a 2017 law in the United Kingdom that retroactively pardoned men cautioned or convicted under historical legislation that outlawed homosexual acts.[15]

Turing has an extensive legacy with statues of him and many things named after him, including an annual award for computer science innovations. He appears on the current Bank of England £50 note, which was released on 23 June 2021, to coincide with his birthday. A 2019 BBC series, as voted by the audience, named him the greatest person of the 20th century.

## [Software Engineering](Software%20Engineering/readme.md)
Software engineering is the branch of computer science that deals with the design, development, testing, and maintenance of software applications. Software engineers apply engineering principles and knowledge of programming languages to build software solutions for end users.

Let’s look at the various definitions of software engineering:

- IEEE, in its standard 610.12-1990, defines software engineering as the application of a systematic, disciplined, which is a computable approach for the development, operation, and maintenance of software.
- Fritz Bauer defined it as ‘the establishment and used standard engineering principles. It helps you to obtain, economically, software which is reliable and works efficiently on the real machines’.
- Boehm defines software engineering, which involves, ‘the practical application of scientific knowledge to the creative design and building of computer programs. It also includes associated documentation needed for developing, operating, and maintaining them.’

### Software engineer tasks and responsibilities
Successful engineers know how to use the right programming languages, platforms, and architectures to develop everything from computer games to network control systems. In addition to building their own systems, software engineers also test, improve, and maintain software built by other engineers. 

In this role, your day-to-day tasks might include:
- Designing and maintaining software systems
- Evaluating and testing new software programs
- Optimizing software for speed and scalability
- Writing and testing code
- Consulting with clients, engineers, security specialists, and other stakeholders
- Presenting new features to stakeholders and internal customers

### Why Software Engineering is Popular?
- Computer Science: Gives the scientific foundation for the software as electrical engineering mainly depends on physics.
- Management Science: Software engineering is labor-intensive work which demands both technical and managerial control. Therefore, it is widely used in management science.
- Economics: In this sector, software engineering helps you in resource estimation and cost control. Computing system must be developed, and data should be maintained regularly within a given budget.
- System Engineering: Most software is a component of a much larger system. For example, the software in an Industry monitoring system or the flight software on an airplane. Software engineering methods should be applied to the study of this type of systems.

## [Integrated Circuits](Integrated%20Circuits/readme.md)
An integrated circuit or monolithic integrated circuit (also referred to as an IC, a chip, or a microchip) is a set of electronic circuits on one small flat piece (or "chip") of semiconductor material, usually silicon. Large numbers of tiny MOSFETs (metal–oxide–semiconductor field-effect transistors) integrate into a small chip. This results in circuits that are orders of magnitude smaller, faster, and less expensive than those constructed of discrete electronic components. The IC's mass production capability, reliability, and building-block approach to integrated circuit design has ensured the rapid adoption of standardized ICs in place of designs using discrete transistors. ICs are now used in virtually all electronic equipment and have revolutionized the world of electronics. Computers, mobile phones and other home appliances are now inextricable parts of the structure of modern societies, made possible by the small size and low cost of ICs such as modern computer processors and microcontrollers.

Very-large-scale integration was made practical by technological advancements in metal–oxide–silicon (MOS) semiconductor device fabrication. Since their origins in the 1960s, the size, speed, and capacity of chips have progressed enormously, driven by technical advances that fit more and more MOS transistors on chips of the same size – a modern chip may have many billions of MOS transistors in an area the size of a human fingernail. These advances, roughly following Moore's law, make the computer chips of today possess millions of times the capacity and thousands of times the speed of the computer chips of the early 1970s.

ICs have two main advantages over discrete circuits: cost and performance. The cost is low because the chips, with all their components, are printed as a unit by photolithography rather than being constructed one transistor at a time. Furthermore, packaged ICs use much less material than discrete circuits. Performance is high because the IC's components switch quickly and consume comparatively little power because of their small size and proximity. The main disadvantage of ICs is the high cost of designing them and fabricating the required photomasks. This high initial cost means ICs are only commercially viable when high production volumes are anticipated.

### Types
Modern electronic component distributors often further sub-categorize integrated circuits:

- Digital ICs are categorized as logic ICs (such as microprocessors and microcontrollers), memory chips (such as MOS memory and floating-gate memory), interface ICs (level shifters, serializer/deserializer, etc.), power management ICs, and programmable devices.
- Analog ICs are categorized as linear integrated circuits and RF circuits (radio frequency circuits).
- Mixed-signal integrated circuits are categorized as data acquisition ICs (including A/D converters, D/A converters, digital potentiometers), clock/timing ICs, switched capacitor (SC) circuits, and RF CMOS circuits.
- Three-dimensional integrated circuits (3D ICs) are categorized into through-silicon via (TSV) ICs and Cu-Cu connection ICs.

## [Operating Systems](Operating%20Systems/readme.md)
An operating system (or OS for short) acts as an intermediary between the user of a computer and computer hardware. The purpose of an operating system is to provide an environment in which an user can execute programs conveniently and efficiently.
An operating system is a software that manages computer hardware. The hardware must provide appropriate mechanisms to ensure the correct operation of the computer system and to prevent user programs from interfering with the proper operation of the system.
An even more common definition is that the operating system is the one program running at all times on the computer (usually called the kernel), with all else being application programs.

### Functions of an OS
- **Convenience**: An OS makes a computer more convenient to use.
- **Efficiency**: An OS allows the computer system resources to be used efficiently.
- **Ability to Evolve**: An OS should be constructed in such a way as to permit the effective development, testing, and introduction of new system functions at the same time without interfering with service.
- **Throughput**: An OS should be constructed so that It can give maximum throughput(Number of tasks per unit time).

### Major functionalities of an OS
- **Resource Management**: When parallel accessing happens in the OS means when multiple users are accessing the system the OS works as Resource Manager, Its responsibility is to provide hardware to the user. It decreases the load in the system.
- **Process Management**: It includes various tasks like scheduling, termination of the process. OS manages various tasks at a time. Here CPU Scheduling happens means all the tasks would be done by the many algorithms that use for scheduling.
- **Storage Management**: The file system mechanism used for the management of the storage. NIFS, CFS, CIFS, NFS, etc. are some file systems. All the data stores in various tracks of Hard disks that all managed by the storage manager. It included Hard Disk.
- **Memory Management**: Refers to the management of primary memory. The operating system has to keep track, how much memory has been used and by whom. It has to decide which process needs memory space and how much. OS also has to allocate and deallocate the memory space.
- **Security/Privacy Management**: Privacy is also provided by the Operating system by means of passwords so that unauthorized applications can’t access programs or data. For example, Windows uses ***Kerberos*** authentication to prevent unauthorized access to data.


## [Memory and Storage](Memory%20and%20Storage/readme.md)
Not added

## [File System](File%20System/readme.md)
Not added

