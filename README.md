# Ruby Instance Variable Modification Bug

This repository demonstrates an uncommon bug in Ruby related to modifying instance variables directly from outside the class definition. The issue arises when one tries to change the value of an instance variable without using a setter method. This can lead to unexpected behavior as the changes won't reflect in the object's state. 

The `bug.rb` file shows the problematic code, while `bugSolution.rb` offers a corrected approach. This is a crucial concept for understanding object-oriented programming in Ruby and preventing subtle bugs.