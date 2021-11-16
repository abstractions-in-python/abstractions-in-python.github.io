# Cooking Times and Dynamic Programming

Dynamic programming is a powerful technique for writing algorithms.  In its essence, dynamic programming consists in a rule for updating a quantity, on the basis of the values of other quantities that are related, or nearby in some sense. 
Once no more updates can be carried out, the quantities provide a solution to some useful problem. 

We apply dynamic programming to the problem of scheduling with both dependencies and delays.  As in the previous chapter, we have a set of tasks to complete, and every task can be performed only once the tasks it depends on have been completed. 
In addition, every task also has a duration. 
We aim not only to find a schedule for performing the tasks that respects the dependencies, but also, a schedule that enables us to do the tasks as quickly as possible, taking into account their duration.  We will see that dynamic programming provides a solution to this problem: the quantities associated with the tasks in dynamic programming will be the task starting times, and the update rule optimizes the starting times taking into account the dependencies. 

## Notebook

* Cooking times and dynamic programming [GitHub](https://github.com/abstractions-in-python/abstractions-in-python.github.io/blob/master/notebooks/Cooking_Times_and_Dynamic_Programming_chapter.ipynb) [Colab](https://drive.google.com/file/d/1eerABCgboPtGoDhFa0C67AMSoDgE21NT/view?usp=sharing)
