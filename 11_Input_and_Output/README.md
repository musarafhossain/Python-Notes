# Input and Output

**Input -** The data given to the computer is called input.
**Output –** The results returned by the computer are called output.

## Output Statements

### `print()` Function 
- The `print()` function is used to print the specified message to the output screen/device. The message can be a string, or any other object.

- #### Syntax:-
```python 
print(objects, sep='character', end='character', file=sys.stdout, flush=False)
```
- **sep -** Separate the objects by given character. Character can be any string. Default is `' '` or can write none.
- **end -** It indicates ending character for the line. Default is `\n` or can write none.
- **file -** An object with a write method. Default is `sys.stdout` or can write none.
- **flush -** A Boolean, specifying if the output is flushed (`True`) or buffered (`False`). Default is `False`.

### `print()`

- This function is used to display a blank line.

### `print("string")`

- When a string is passed to the function, the string is displayed as it is.

- #### Example 
```python
print("Hello, Musaraf")  # Hello, Musaraf
```

### `print(object)`

- We can pass objects like `list`, `tuples` and `dictionaries` to display the elements of those objects.

- #### Example 
```python
data = [10, 20, -50, 21.3, 'Musaraf']
print(data)   # [10, 20, -50, 21.3, 'Musaraf']
```

### `print("string", sep='')`

- It separates string with given sep character. Character can be any string. Default is `' '` or can write none.

- #### Example 
```python
print("Hello", "World", sep='**')  # Hello**World
```

### `print("string", end='')`

- When ending character is passed. It prints given character at the end. Default is `\n` or can write none.

- #### Example 
```python
print("Hello", end=' ')
print("World")
```
- #### Output
```bash
Hello World
```

### `print(variable list)`

- This is used to display the value of a variable or a list of variable.

- #### Example 
```python
x = 20
y = 30
print(x, y)
```
- #### Output
```bash
20 30
```

### `print("String", variable list)`

- This is used to display the string along with variable.

- #### Example 
```python
m = 40
print("Value: ", m) 
```
- #### Output
```bash
Value: 40
```

## Input Statements

### `input()`
- This function is used to accept input from keyboard. 
- This function will stop the program flow until the user gives an input and end the input with the return key. 
- Whatever user gives as input, input function convert it into a `string`. If user enters an integer value still `input()` function convert it into a `string`. 
- So if you need an integer you have to use type conversion. 
- #### Syntax:-
```python 
input("prompt")
```
>**Note:** `prompt` is a string or message, representing a default message before input. It is optional
- #### Exmaple
```python
num1 = int(input("Enter Number 1: "))
num2 = int(input("Enter Number 2: "))
result = num1 + num2
print("Sum is :", result)
```
- #### Output
```bash
Enter Number 1: 10
Enter Number 2: 20
Sum is : 30
```