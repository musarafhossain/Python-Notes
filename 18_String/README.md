# String

- String represents group of characters. Strings are enclosed in double quotes or single quotes. The `str` data type represents a String.
- #### Example:- 
    `"Hello", "Musaraf", 'India'`
    `str1 = "Bharat"`

# Creating String
### Single Quotes
```python
str1 = 'Musaraf Hossain'
```
### Double quotes
```python
str2 = "Musaraf Hossain"
```
### Triple Single Quotes 
This is useful to create strings which span into several lines. 
```python
str3 = '''Hello Guys
          My name is
          Musaraf Hossain'''
```
### Triple Double Quotes 
This is useful to create strings which span into several lines. 
```python
str4 = """Hello Guys
          My name is
          Musaraf Hossain"""
```
### Double Quote inside Single Quotes
```python
str5 = 'Hello "Musaraf" How are you'
```
### Single Quote inside Double quotes
```python
str6 = "Hello 'Musaraf' How are you"
```
### Using Escape Characters
```python
str7 = “Hello \nHow are You ?”
```
### Raw String 
Row string is used to nullify the effect of escape characters.
```python
str8 = r"Hello \nHow are You ?"
print(str8)         # Output: Hello \nHow are You ?
```
# Index

- Index represents the position number of characters in a string.
- #### Example:- 
```python
str1 = "AbuMusaraf"
```
![](./image1.png)

# String Length

- Length of string represents the number of characters in a string.
- `len()` Function is used to get length of string.
- #### Example:- 
```python
str1 = Musaraf
n = len(str1)       # Output: 7
```

# Accessing String
## Using Index
```python
str1 = "Musaraf"
print(str1)         # Musaraf
print(str1[0])      # M
print(str1[1])      # u
print(str1[2])      # s
print(str1[3])      # a
print(str1[-1])     # f
```
## Using loop
```python
str1 = "Musaraf"
for c in str1:
    print(c)

for i range(len(str1)):
    print(str1[i])

i = 0
while i < len(str1) :
    print(str1[i])
    i+=1
```

# Mutable and Immutable Object
## Mutable Object 
- Mutable objects are those object whose value or content can be changed as and when required.
- #### Example:- 
    `List`, `Set`, `Dictionaries` 

## Immutable Object 
- Immutable objects are those object whose value or content can not be changed.
- #### Example:- 
    `Numbers`, `String`, `Tuple`

# Immutable String

In Python, Strings are immutable object which means it’s value or content can not be changed.
```python
str1 ="Musaraf"
str1[4] ="i" # TypeError: 'str' object does not support item assignment
```
# Slicing Operator

- Slicing on String can be used to retrieve a piece of the string. Slicing is useful to retrieve a range of elements. 
- #### Syntax:-
```python 
new_string_name = string_name[start:stop:stepsize]
```
- `start` – It represents starting point. By default its 0
- `stop` – It represents ending point.
- `stepsize` – It represents step interval. By default It is 1
- If start and stop are not specified then slicing is done from `0th` to `n-1th`  elements.
- Start and Stop can be negative number.
- #### Example:-
```python
str1 = "Musaraf"
print(str1[0:6:2])      # Msr
```

# Repetition Operator

- Repetition operator is used to repeat the string for several times. It is denoted by `*`.
- #### Example:-
```python 
x = "$" * 7
print(x)            # $$$$$$$
str1 = "Musaraf"
print(str1 * 5)     # MusarafMusarafMusarafMusarafMusaraf
```

# Concatenation Operator

- Concatenation operator is used to join two string. It is denoted by `+`.
- #### Example:-
```python
str1 = "Musaraf"
str2 = "Hossain"
str3 = str1 + str2
print(str3)         # MusarafHossain
```

# Comparing String

| Operator | Meaning |
|----------|---------|
| `<` | Less than |
| `>` | Greater than |
| `<=` | Less than equal to |
| `>=` | Greater than equal to |
| `==` | Equal to |
| `!=` | Not equal to |

#### Example:-
```python
str1 = "apple"
str2 = "banana"

print("str1 < str2:", str1 < str2)     # True, because 'a' comes before 'b'
print("str1 > str2:", str1 > str2)     # False
print("str1 <= str2:", str1 <= str2)   # True
print("str1 >= str2:", str1 >= str2)   # False
print("str1 == str2:", str1 == str2)   # False
print("str1 != str2:", str1 != str2)   # True
```