# Programming Abstractions in Python
### Luca de Alfaro
Copyright 2019-21, [Luca de Alfaro](https://luca.dealfaro.com). [License: CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

## Introduction

This is the online textbook Programming Abstractions in Python, written for the class by the same name at the University of California, Santa Cruz. 

The idea of the book, and of the class, consists in teaching students to think about software in terms of objects that have primitive operations.  When confronted with a new problem to solve, one should consider what are the objects that are useful for representing the problem, and what operations can be defined on those objects that solve the problem.  The operations on objects are often best understood as mathematical operations on the set of objects: considering the properties of the operations leads to cleaner, and more general, solutions. 

The book is articulated into five parts:

* **Methods:**  This part provides a refresher of the Python programming language, and provides an introduction to recursion and generators. 
* **Structures:** Here we introduce the central message of the class: to solve a problem, think at the problem in terms of _objects_ that have _operations_ defined on them. We build a clone of [Pandas](https://pandas.pydata.org/), we introduce data structures for representing subsets of real numbers, we develop a motion detection algorithm for images, and more. 
* **From Symbolic Expressions to Machine Learning:** We introduce the idea of representing expressions via trees, and evaluating them with respect to a variable assignment.  We then develop symbolic differentiation, autogradient, and we build a simplified clone of [PyTorch](https://pytorch.org/).   
* **Graphs and dynamic algorithms:** A part on graphs dynamic algorithms introduces graphs, along with the fundamental algorithsm for graph exploration. We then present some ideas about dynamic solution methods that are fundamental to problem solving in many areas of computer science.
* **Search:** We introduce the fundamental guess-propagate-recur paradigm that is at the core of most search procedures, and we illustrate it on Sudoku and SAT. 

In the course of the book, we will provide simple implementations of well-known problems.  Among other things, we will reimplement the machine-learning framework [PyTorch](https://pytorch.org/), albeit in a simplified pure-Python setting; we will reimplement the core of [Pandas](https://pandas.pydata.org/), and we will write Sudoku and Boolean SAT solvers.  All these implementations will be concise, minimalistic, and yet powerful, and we hope that they can serve as illustration of how to approach non-trivial software and algorithmic problems. 

### Book Format

The book chapters consist in [Jupyter notebooks](https://jupyter.org/).  Jupyter notebooks allow [literate programming](https://www-cs-faculty.stanford.edu/~knuth/lp.html): one can write, in the same place, both the text and mathematics that explains the high-level concepts, and their implementations into code.  The notebooks provided here form the book.  

The notebooks occasionally contain holes, where you have to fill in code: we leave to you the pleasure and satisfaction of implementing the most fun, and interesting, portions. This is one of the benefits of using Jupyter notebooks: you can play with the material and the code we give you, experiment, and see the effects right away. Instructors can contact the author at luca@ucsc.edu to obtain complete versions of the notebooks, which can be run during a classroom lecture. 

### What this course is, and is not

This course focuses on the _conceptual_ aspects of programming and software development.  The course is _not_ an introduction to particular tools for software development.  In particular, the course does _not_ cover topics such as the use of version control, command line, code editors and development environments, Python distributions, and Python package management. 
These are all worthy topics, of course; however, they are not the focus of the class. 
At UCSC, where the class is taught, students learn these topics in other classes. 

Tools and development environments are important, but they also change and evolve as time passes; the principles covered in this class can be useful across environment and across programming languages. 

### Acknowledgements

Lindsey Kuper and Peter Alvaro have taught this class at UCSC, and provided invaluable feedback and suggestions. 
The author is much indebted to Philippe Bossut for inspiration about the approach, and to Massimo Di Pierro for his many suggestions on topics to cover and methods. 

### Accessing the Content

We provide here the Jupyter Notebooks constituting the chapters, along with the video lectures that accompany them. 
To access a Jupyter Notebook, you have three choices: you can either follow the link here on GitHub, you can visit the notebooks on Google Colab, or you can download it and run it with Jupyter on your own laptop.
Using Colab [requires a bit of setup](/colab_setup.html), but has the advantage that you can directly play with the lecture material. 

## Chapters

### Part I: Methods

* [Introduction to Python 3](/0_introduction_to_python_3.html)
* [Data structures and their access characteristics](1_1_data_structures.html)
* [Recursion](1_2_recursion.html)
* [Generators]()

### Part II: Structures

* [Classes](/2_1_classes.html) 
* [Sock drawers and arithmetic dictionaries](/2_2_sock_drawers.html)
* [Event-driven simulation](/2_3_event_driven_simulation.html)
* [Introduction to Numpy](/2_4_introduction_to_numpy.html)
* [Stream averages and motion detection]()

### Part III: From Symbolic Expressions to Machine Learning

* [Mathematical expressions]()
* [Expressions as classes]()
* [From expressions to machine learning]()
* [Machine learning with PyTorch]()

### Part IV: Graphs and Dynamic Algorithms

* [Graphs]()
* [Scheduling with dependencies]()
* [Cooking times and dynamic programming]()
* [Finding a route in a graph]()

### Part V: Search

* [Sudoku]()
* [SAT]()
* [From Sudoku to SAT]()

### Other topics

The following topics are not used as part of the class, but may be of general interest. 

* [Counting stacks and queues]()
* [Sparse arrays]()
* [Data tables]()
* [An interval algebra]()
* [Regions]()
* [Light and filters]()

