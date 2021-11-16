# Scheduling with dependencies

Scheduling is an important topic in computer science.  Often one needs to do a set of tasks that have dependency relations among them.  For example, when you cook, you need to dice an onion before putting the onion in a pan, and you need to put the onion in a pan before you can cook the onion.  In code, you may need to compile `foo.c` into `foo.o`, before you can link `foo.o` with `somelib.a`. 

Here, we will see how graphs can be used to represent scheduling with dependencies, and we will see how to schedule the tasks, and how to handle the need of redoing some of the tasks. 
To make this more fun, we will be using a recipe as the running example.

## Notebook

* Scheduling with dependencies [GitHub](https://github.com/abstractions-in-python/abstractions-in-python.github.io/blob/master/notebooks/Scheduling_with_Dependencies_chapter.ipynb) [Colab](https://drive.google.com/file/d/1oDkP-a6jKGMMEHPYQvlbfsX355PCd3wX/view?usp=sharing)