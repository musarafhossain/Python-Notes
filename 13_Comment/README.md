# Comment

- Comments are non-executable statements. A Comment is used to describe the feature of a program. Comment helps to understand our program, not only ourselves but also other programmer. 
- There are two type of programs:- 
    - ### Single Line Comment
    - ### Multi line Comment

## Single Line Comment

- These comments start with a hash symbol (#).
- #### Example:- 
```python
# I am single Line Comment
# This is my first Python Program
# Adding two numbers
```

## Multi Line Comment

- There is no concept of multi line comment in python but we can create string starting and ending with triple double quotes (`"""`) or triple single quotes (`'''`) which can be used as block of comments. 
- Since strings are not assigned to any variable, then they are removed from memory by the garbage collector and hence these can be used as comments. 
- It is not recommended to use triple double quotes or triple single quotes for writing comments as it internally occupy memory and would waste time of the interpreter since the interpreter has to check them. 
- #### Example:-
```python 
"""
Comment Line 1
Comment Line 2
Comment Line 3
"""

'''
Comment Line 1
Comment Line 2
Comment Line 3
'''
```
