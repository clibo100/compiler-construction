# compiler-construction
Notes and Materials for a course on Compiler Construction Spring 2019 at Chapman University.

Quick links to BNFC installation instructions and other documentation, to be used in addition to the official [BNFC tutorial](http://bnfc.digitalgrammars.com/tutorial/bnfc-tutorial.html) and the  book [Implementing Programming Languages](http://www.grammaticalframework.org/ipl-book/):

- [BNFC: basic installation instructions](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation.md)
- [BNFC: adding the Java lexer and parser](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation-java.md)
- [BNFC: self check](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md)
- BNFC/Happy parser:
  - The BNFC/Happy [`.info`-files](https://hackmd.io/s/ryllVQdIN#How-to-create-the-info-file-of-a-Happy-parser) and an example of [shift-reduce parsing](https://hackmd.io/s/ryllVQdIN).
  - How to eliminate [shift/reduce and reduce/reduce](https://hackmd.io/s/rJoVGDh84) conflicts.
  - Understanding [LALR(1) parsing](https://hackmd.io/s/S11sLzo84) with a worked example.
- [LBNF](https://hackmd.io/s/SyJowOgD4): Some tips on the language in which a BNF-grammar is written.
  
Lecture by Lecture:

- [Lecture 1.1](lecture-1.1.md): Organisation, Assessment, Short introduction to parsing.

- Lab 1.2: Discussion of Assignment 1.
  - [Assignment 1](https://hackmd.io/s/HyaDeaXzN#) 
  - due Wed, Feb 6, see [Lecture 1.1](lecture-1.1.md) for details

- [Lecture 1.3](https://hackmd.io/s/S110eS-VE#): How to implement a state machine and why do Java and Python not have gotos? **Homework:** Read the articles referenced in [the lecture](https://hackmd.io/s/S110eS-VE).

- [Lecture 2.1](http://www.grammaticalframework.org/ipl-book/slides/1-slides-ipl-book.pdf): A brief introduction to compiler construction from Chapter 1 of [the book](http://www.grammaticalframework.org/ipl-book/). **Homework:** Read [Chapter 1](http://www.cse.chalmers.se/edu/year/2012/course/DAT150/lectures/plt-book.pdf).

- [Lecture 2.2](lecture-2.2.md): Determinstic Finite Automata. **Homework:** Exercise 2.2.4 (possibly 2.2.5 and 2.2.6) and Exercise 2.2.10 (possibly 2.2.11) from [Introduction to Automata Theory]( https://mcdtu.files.wordpress.com/2017/03/introduction-to-automata-theory.pdf). These exercises are relevant for tests and final.

- Lecture 2.3: **How to build a compiler/interpreter in 50min**. We looked at the [slides](http://www.grammaticalframework.org/ipl-book/slides/2-slides-ipl-book.pdf) up to page 35, see also Chapter 2 of [the book](http://www.cse.chalmers.se/edu/year/2012/course/DAT150/lectures/plt-book.pdf). For installation  introductions see the [BNFC homepage](http://bnfc.digitalgrammars.com) or my [BNFC installation instructions](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation.md). **Homework:** First install Haskell (not necessary if you use the windows binaries), then install BNFC. *Deadline: Monday, Feb 11, before class* (If there are problems with installation we will try to sort it out on Monday in class.)

- Lab 3.1: The aim of the lab is for everybody to be able to replicate my [BNFC installation instructions](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation.md). *From today on I will assume that everybody has bnfc installed and is able to run the calculator. Let me know if this is not the case.*

- Lecture 3.2: The aim of this lecture is to understand more about parsing. I link the grammars of [C](https://cs.wmich.edu/~gupta/teaching/cs4850/sumII06/The%20syntax%20of%20C%20in%20Backus-Naur%20form.htm) and [Java](https://docs.oracle.com/javase/specs/jls/se11/html/jls-19.html). In the lecture we explained how the grammar of C-- of the [BNFC tutorial](http://bnfc.digitalgrammars.com/tutorial/bnfc-tutorial.html) works. Then we started on Exercise 2 in  [BNFC self check](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md). Trying to find the bug in the program of Exercise 2 is **Homework** (to do before the class on Friday, Feb 15, when we will look at this together).

- Lecture 3.3: The aim of the coming labs/lectures is to finish the material of Chapter 2 in [the book](http://www.cse.chalmers.se/edu/year/2012/course/DAT150/lectures/plt-book.pdf) and the [slides](http://www.grammaticalframework.org/ipl-book/slides/2-slides-ipl-book.pdf) and of the [BNFC tutorial](http://bnfc.digitalgrammars.com/tutorial/bnfc-tutorial.html). **Homework:**  [Install the Java lexer and parser](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation-java.md) and finish Exercise 2 of the [BNFC self check](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md).

- Lab/Lecture 4.1: [Working towards Assignment 2](http://www.grammaticalframework.org/ipl-book/assignments/assignment1/assignment1.html).
[Install the Java lexer and parser](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-installation-java.md).

- Lab 4.2: The aim is to sort out any remaining problems with installing BNFC. For those who missed this in class there is a **Homework:** Exercise 0 of the [BNFC self check](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md).

- Lecture 4.3: How to build a parse tree, illustrated by [Exercise 2](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md). **Homework:** Exercise 3 of the [BNFC self check](https://github.com/alexhkurz/compiler-construction/blob/master/BNFC-example.md).

- Assignment 2: [Grammar and Parser for C++](http://www.grammaticalframework.org/ipl-book/assignments/assignment1/assignment1.html). Deadline for the first test file Thursday, Feb 28, (11:59 pm PST), for the rest of the assignment Sunday, March 10, (11:59 pm PST).  

  - Read Section 2.10 of [Implementing Programming Languages](http://www.cse.chalmers.se/edu/year/2012/course/DAT150/lectures/plt-book.pdf). See also `bnfc/examples/cpp/cpp.cf`.
  - The [LBNF reference](https://bnfc.readthedocs.io/en/latest/lbnf.html#lbnf-in-a-nutshell) can be a good resource, for example the section on [terminators and separators](https://bnfc.readthedocs.io/en/latest/lbnf.html#terminator).

- Lecture 5.1: Nondeterminstic Finite Automata](https://hackmd.io/s/ByjJ8eWUE). **Homework:** Exercise 2.3.1 and 2.3.2 from [Introduction to Automata Theory]( https://mcdtu.files.wordpress.com/2017/03/introduction-to-automata-theory.pdf). These exercises are relevant for tests and final.
  
- [Lecture 5.2](https://hackmd.io/s/SJv6u2GL4#): Composing Automata

- [Lecture 5.3](https://hackmd.io/s/rkA6Af484#): Regular Expressions. **Homework:** Exercise 3.1.1, 3.2.4, 3.2.5 from [Introduction to Automata Theory]( https://mcdtu.files.wordpress.com/2017/03/introduction-to-automata-theory.pdf). These exercises are relevant for tests and final.

- [Lecture 6.1](https://hackmd.io/s/ryllVQdIN#): How to produce a `.info`-file? How does shift-reduce parsing work?  **Homework:** Do the exercise from the lecture notes. These exercises are relevant for tests and final.

- [Lecture/Lab 6.2/6.3](https://hackmd.io/s/rJoVGDh84#): How to eliminate shift/reduce and reduce/reduce conflicts. **Homework:** Do the exercise from the lecture notes. These exercises are relevant for Assignment 2.

- [Lecture 7.1](https://hackmd.io/s/S11sLzo84#): How does the LALR(1) parser generated by BNFC and Happy work?  **Homework:** Do the exercise from the lecture notes. This exercise is relevant for tests and final.

- [**Test in Class 7.2 on Wed March 13**](https://hackmd.io/s/ry_CIrSwE)
  
- [Bonus Lecture: Mathematics as a Programming Language, Part 1](https://hackmd.io/s/ByGLTvFDE)

- Lecture 8.1: Wrapping up Chapter 2 and 3 of [the book](http://www.cse.chalmers.se/edu/year/2012/course/DAT150/lectures/plt-book.pdf).In particular, we discussed in details the  [slides for Chapter 2](http://www.grammaticalframework.org/ipl-book/slides/2-slides-ipl-book.pdf) page 18 and 23-42 from the point of view of type checking and the [slides for Chapter 3](http://www.grammaticalframework.org/ipl-book/slides/3-slides-ipl-book.pdf) page 27-32 emphasising why regular expressions and finite automata are not strong enough to do the parsing. Note that this explains why many programming languages do not allow nested comments. **Homework:** Read Chapter 2 of [the book](http://www.grammaticalframework.org/ipl-book/) (again) and let me know about any questions that may still remain.

- Lecture 8.2: We finished with the [slides for Chapter 3](http://www.grammaticalframework.org/ipl-book/slides/3-slides-ipl-book.pdf) looking in detail at pages 33-46 explaining the differences between and respective advantages of LL and LR parsing. (The content of pages 
47-59 was discussed already in detail during Lectures 6.1-7.1.) **Homework:** Read Chapter 3.1 to 3.8 of [the book](http://www.grammaticalframework.org/ipl-book/) and let me know about any questions that may still remain.

- Lecture 8.3: Working towards Assignment 3, the [Type Checker for CPP](http://www.grammaticalframework.org/ipl-book/assignments/assignment2/assignment2.html). Main source is Chapter 4 of the book. [Slides for Chapter 4](http://www.grammaticalframework.org/ipl-book/slides/4-slides-ipl-book.pdf). **Homework:** Read Chapter 3.9 to 4.3 of [the book](http://www.grammaticalframework.org/ipl-book/) and be prepared to ask any questions that you might have  on this next Monday.

- Lecture 9.1: continued from above ...  **Homework:** Read Chapter 4.4 of [the book](http://www.grammaticalframework.org/ipl-book/) and be prepared to ask any questions that you might have  on this next Wednesday.

- Lecture 9.3: continued from above ...  in-class exercise on how to read and write typing rules and on how to build a proof tree for type checking and type inference. **Homework:** Read Chapter 4.5 of [the book](http://www.grammaticalframework.org/ipl-book/) and be prepared to ask any questions.

- Lecture 10.1: continued from above ... **Homework:** Read Chapter 4.6 of [the book](http://www.grammaticalframework.org/ipl-book/) and be prepared to ask any questions.

- Lecture 10.2: Introduction to 

  - [Assignment 3](http://www.grammaticalframework.org/ipl-book/assignments/assignment2/assignment2.html). You need access to the [github repository](https://github.com/ChapmanCPSC/compiler-assignments) for this assignment (send me an email with your github name if you dont have already access). There you find more information in the README files. A good place to ask questions is Slack so that everybody will have access to the same information.
  
  - Deadline **Friday April 26 11:59 pm**.

  
- Lecture 10.3: We extracted the typing rule for multiplication from the code of [Typechecker.hs](https://github.com/ChapmanCPSC/compiler-assignments/blob/master/Typechecker/Haskell/src/TypeChecker.hs), lines 127-156. Read Chapter 4.11.

- Lecture 11.1: [Slides for Chapter 4](http://www.grammaticalframework.org/ipl-book/slides/4-slides-ipl-book.pdf) pages 24-29. Read Chapter 4.7.

- Lecture 11.2: [Slides for Chapter 4](http://www.grammaticalframework.org/ipl-book/slides/4-slides-ipl-book.pdf) pages 57-68. Read Chapter 4.12

- Lecture 11.3: [Slides for Chapter 4](http://www.grammaticalframework.org/ipl-book/slides/4-slides-ipl-book.pdf) pages 29-44. Read Chapter 4.10.

- Lecture 12.1: [Slides for Chapter 4](http://www.grammaticalframework.org/ipl-book/slides/4-slides-ipl-book.pdf) pages 45-56. 

- Exercise Class 12.2: Shift-reduce parsing for Test 2, Wed May 1.
  - [Sample Test 2](https://hackmd.io/s/SklvVeAc4)

- Exercise Class 12.3: (continued from above): concrete and abstract syntax trees

- Lecture 13.1: Assignment 4, the [Interpreter for CPP](http://www.grammaticalframework.org/ipl-book/assignments/assignment3/assignment3.html). Main source is Chapter 5 of the book. [Slides for Chapter 5](http://www.grammaticalframework.org/ipl-book/slides/5-slides-ipl-book.pdf). **Homework:** Read Chapter 5.?? of [the book](http://www.grammaticalframework.org/ipl-book/).

- Coming up: Assignment 4

  - 


