# Data Type

- Datatype represents the type of data stored into a variable or memory.
- **Type of Data type :-**
    - #### Built-in Data type
    - #### User Defined Data type

# Built-in Datatype

- These datatypes are provided by Python Language.
- **Following are the built-in data type :-** 
    - #### None Type
    - #### Numeric Types 
    - #### Sequences
    - #### Sets
    - #### Mappings

## None Type

- None datatype represents an object that doesn’t contain any value.
- #### Example :-
```python
name = None
```
## Numeric Type / Number

- Following are the Numeric Data type:- **Int, Float, Complex**  

### Int
- The int datatype represents an integer number. An integer number without any decimal point or fraction part. In Python, It is possible to store very large integer number as there is no limit for the size of an int datatype.
- #### Example :-
```python
x = -1002
y = 10
pin_code = 564512
```

### Float
- The float data type represents floating point numbers. A floating point number is a number that contains a decimal point.
- #### Example :-
```python
price = 25.56
run_rate = -0.8
value = 5.1e5
```
> **Note:** 5.1e5 (It’s scientific notation where e or E represents exponentiation which represents the power of 10)

### Complex 
- A complex number is a number that is written in the form of `a + bj` or `a + bJ`. Where,
`a` = Real Part of the number
`b` = Imaginary part of the number
`j` or `J` = Square root value of `-1`
`a` and `b` may contain integer or float number.
- #### Example :-
```python
a = 5+7j
b = 0.8+2j
com = 5+7j
```

## Bool type

- The bool datatype represents boolean value `True` or `False`. Python internally represents `True` as `1` and `False` as `0`.
- #### Example :-
```python
isLogin = True
isAdmin = False
print(True + True)  #Output: 2
print(True – False) #Output: 1
```

## Sequence Type

- Following are sequence type:- **String, List, Tuple, Range**

### String 
- String represents group of characters. Strings are enclosed in `double` quotes or `single` quotes. 
- #### Example :-
```python
str1 = "Musaraf"
str1 = 'Musaraf'
```
### List 
- A list represents a group of elements. A list can store different types of elements which can be modified. Lists are dynamic which means size is not fixed. Lists are represented using square bracket `[]`.
- #### Example :-
```python
data = [10, 20, -50, 21.3, 'Musaraf']
```

### Tuple 
- A tuple contains a group of elements which can be different types. It is similar to List but Tuples are read-only which means we can not modify it’s element. Tuples are represented using parentheses `()`.
- #### Example :-
```python
data = (10, 20, -50, 21.3, 'Musaraf)
```
### Range 
- Range represents a sequence of numbers. The numbers in the range are not modifiable.
- #### Example :-
```python
# range(Initial, Final, Step)
rg = range(5)           # 0 1 2 3 4 
rg = range(10, 20, 2)	# 10 12 14 16 18
```

## Set Type

- A set is an unordered collection of elements much like a set in mathematics. 
- The order of elements is not maintained in the sets. It means the elements may not appear in the same order as they are entered into the set. 
- A set does not accept duplicate elements. 
- Sets are unordered so we can not access its element using index.
- Sets are represented using curly brackets `{}`.
- #### Example :-
```python
data = {10, 20, 30, "Musaraf", "Hossain", 40}
data = {10, 20, 30, "Musaraf", "Hossain", 40, 10, 20}
```
## Mapping Type/ dict / Dictionary

- A map represents a group of elements in the form of key value pairs.
- #### Example :-
```python
data = {101: 'Musaraf', 102: 'Abu', 103: 'Neela' }
data = {'Musaraf': 2000, 'Abu': 3000, 'Neela': 8000, }
```
## Character

- There is no concept of char data type in Python to represent individual character.

# User Defined Data type

- #### Array
- #### Class
- #### Module

