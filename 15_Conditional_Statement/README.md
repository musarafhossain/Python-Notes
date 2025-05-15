# Conditional Statement

--- 

# `if` Statement

- It is used to execute an instruction or block of instructions only if a condition is fulfilled.
- #### Syntax: -
```python
if (condition):
    statement
Rest of the Code

if (condition):
    statement1
    statement2
Rest of the Code
```
- #### Example: -
```python
if(5>2):
    print('5 is greater than 2')
```
> **Note:** If there is single statement it can be written in one line.
- #### Example:-
```python 
if (condition): Statement
```

### Flowchart
![](/14_Conditional_Statement/image1.png)

## Nested If Statement

- #### Syntax :
```python
if (condition):
    block of statements
    if(condition):
        block of statements
    if(condition):
        block of statements
if(condition):
    block of statements
Rest of the code
```

- #### Example:-
```python 
age = 25
has_license = True
no_traffic_violations = True

if age >= 18:
    print("You are an adult.")
    
    if has_license:
        print("You have a driving license.")
        
        if no_traffic_violations:
            print("You are eligible for a safe driver discount!")
    else:
        print("You need to get a driving license first.")
else:
    print("You are not eligible to drive yet.")

print("End of check.")
```
## If Statement with Logical Operator

- #### Syntax :
```python
if ( (condition1) and (condition2) ):
    Statement
Rest of the Code

if ( (condition1) or (condition2) ):
    Statement
Rest of the Code
```

- #### Example:-
```python 
age = 20
has_ticket = True

# Using 'and' logical operator
if age >= 18 and has_ticket:
    print("You are allowed to enter the movie theater.")

# Using 'or' logical operator
if age < 18 or not has_ticket:
    print("You are not allowed to enter the movie theater.")

print("Check complete.")
```

# `if-else` Statement

- `if`…`else` statement is used when a different sequence of instructions is to be executed depending on the logical value(`True`/`False`) of the condition evaluated.
- #### Syntax: - 
```python
if(condition):
    Statement 1
    Statement 2
else:
    Statement 3
    Statement 4
Rest of the Code
```
- #### Example:-
```python 
temperature = 15

if temperature >= 20:
    print("It's warm outside.")
    print("You can wear light clothes.")
else:
    print("It's cold outside.")
    print("You should wear a jacket.")

print("Weather check complete.")
```

### Flowchart
![](/14_Conditional_Statement/image2.png)

## Nested `if-else` Statement

- In nested `if`…`else` statement, an entire `if`…`else` construct is written within either the body of the `if` statement or the body of an `else` statement.

- #### Syntax :-
```python
if(condition_1):
    if(condition_2):
        Statement 1
    else:
        Statement 2
else:
    if(condition_3):
        Statement 3
    else:
        Statement 4
Rest of the Code
```
- #### Example:-
```python
age = 22
has_id = False
is_student = True

if age >= 18:
    if has_id:
        print("Access granted: You are an adult with valid ID.")
    else:
        print("Access denied: ID is required.")
else:
    if is_student:
        print("Access granted: You are a student, even though under 18.")
    else:
        print("Access denied: You are underage and not a student.")

print("Verification complete.")
```

# `if-elif` Statement

- To show a multi-way decision based on several conditions, we use `if` `elif` statement.
- #### Syntax :-
```python
if(condition_1):
    Statement 1
elif(condition_2):
    Statement 2
elif(condition_3):
    Statement 3
elif(condition_n):
    Statement n
Rest of the Code
```
- #### Example:-
```python
marks = 75

if marks >= 90:
    print("Grade: A")
elif marks >= 80:
    print("Grade: B")
elif marks >= 70:
    print("Grade: C")
elif marks >= 60:
    print("Grade: D")

print("Grading complete.")
```

# `if-elif-else` Statement

- To show a multi-way decision based on several conditions, we use `if` `elif` `else` statement.
- #### Syntax :-
```python
if(condition_1):
    Statement 1
elif(condition_2):
    Statement 2
elif(condition_3):
    Statement 3
elif(condition_n):
    Statement n
else:
    Statements x
Rest of the Code

```
- #### Example:-
```python
marks = 75

if marks >= 90:
    print("Grade: A")
elif marks >= 80:
    print("Grade: B")
elif marks >= 70:
    print("Grade: C")
elif marks >= 60:
    print("Grade: D")
else:
    print("Grade: F")

print("Grading complete.")
```

### Flowchart
![](/14_Conditional_Statement/image3.png)

---

# `match-case` Statement

* Introduced in **Python 3.10**, the `match-case` statement is Python’s version of **switch-case**, used for **pattern matching**.
* It allows checking a value against **multiple patterns**, making the code **cleaner and more readable** compared to multiple `if-elif-else`.

* #### Syntax:

```python
match variable:
    case pattern1:
        # block of code
    case pattern2:
        # block of code
    case _:
        # default case (like else)
```

* #### Example:

```python
command = "start"

match command:
    case "start":
        print("System is starting...")
    case "stop":
        print("System is stopping...")
    case "restart":
        print("System is restarting...")
    case _:
        print("Unknown command")
```