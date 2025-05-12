# Operators

- An operator is a symbol that performs an operation.
- ### Arithmetic Operators
- ### Relational Operators / Comparison Operators
- ### Logical Operators 
- ### Assignment Operators
- ### Bitwise Operators
- ### Membership Operators
- ### Identity Operators


---

## 🔢 Arithmatic Operators
- Arithmetic Operators are used to perform basic arithmetic operations like addition, subtraction, division etc.

| Operators | Meaning      | Example | Result |
|-----------|--------------|---------|--------|
| `+`       | Addition     | 5 + 2   | 7      |
| `-`       | Subtraction  | 5 - 2   | 3      |
| `*`       | Multiplication | 5 * 2 | 10     |
| `/`       | Division     | 10 / 2  | 5      |
| `%`       | Modulus      | 5 % 2   | 1      |
| `**`       | Exponent      | 5 ** 2   | 25      |
| `//`       | Integer Division/ Floor Division      | 5 // 2   | 2      |

---

### 💻 Code Example:
```python
print(5 + 2);  # 7
print(5 - 2);  # 3
print(5 * 2);  # 10
print(10 / 2); # 5
print(5 % 2);  # 1
print(5 ** 2); # 25
print(5 // 2); # 2
```

---

## 📝 Assignment Operators

Assignment operators are used to perform arithmetic operations while assigning a value to a variable.

---

| Operators | Example | Equivalent Expression (`m = 15`) | Result |
|-----------|---------|-------------------------|--------|
| `+=`      | `m += 10` | `m = m + 10`             | 25     |
| `-=`      | `m -= 5`  | `m = m - 5`              | 10     |
| `*=`      | `m *= 2`  | `m = m * 2`              | 30     |
| `/=`      | `m /= 5`  | `m = m / 5`              | 3      |
| `%=`      | `m %= 4`  | `m = m % 4`              | 3      |
| `**=`      | `m **= 4`  | `m = m ** 2`             | 225      |
| `//=`      | `m //= 4`  | `m = m // 10`              | 1      |

---

### 💻 Code Example:
```python
m = 15;
m += 10;
print(m); # 25
```

---

## 🔍 Relational/Comparison Operators

- Relational operators are used to compare the value of operands (expressions) to produce a logical value. A logical value is either `True` or `False`.

| Operators | Meaning               | Example    | Result |
|-----------|------------------------|------------|--------|
| `<`       | Less than              | 5 < 2      | False  |
| `>`       | Greater than           | 5 > 2      | True  |
| `<=`      | Less than or equal to  | 5 <= 5     | True  |
| `>=`      | Greater than or equal to | 5 >= 6   | False  |
| `==`      | Equal to       | 5 == 5   | True   |
| `!=`      | Not equal to              | 5 != 2     | True   |

---

### 💻 Code Example:
```python
print(5 < 2)     # False
print(5 > 2)     # True
print(5 == 5)    # True
```

---

## 🧠 Logical Operators

- Logical operators are used to connect more relational operations to form a complex expression called logical expression. A value obtained by evaluating a logical expression is always logical, i.e. either `True` or `False`.

| Operators | Meaning      |
|-----------|--------------|
| `and`     | Logical AND  | 
| `or`      | Logical OR   | 
| `xor`     | Logical XOR  |

### and
| Operand 1 | Operand 2 | Result |
|-----------|-----------|--------|
|True|True|True
|True|False|False
|False|True|False
|False|False|False
|True|Expression|Expression
|False|Expression|False

> **Note :** `True` and `Expression1` and `Expression2` = `Expression2`
`False` and `Expression1` and `Expression2` = `False`

### or
| Operand 1 | Operand 2 | Result |
|-----------|-----------|--------|
|True|True|True
|True|False|True
|False|True|True
|False|False|False
|True|Expression|True
|False|Expression|Expression

> **Note :** `True` and `Expression1` and `Expression2` = `True`
`False` and `Expression1` and `Expression2` = `Expression1`

### not
| Operand | Result |
|---------|--------|
| True | False
| False | True

---

### 💻 Code Example:
```python
print(5>2 and 6<9) # True
print(5<2 or 6<9)  # False
```

---

## 🧮 Bitwise Operators

- Bitwise operators are used to perform operations at binary digit level. These operators are not commonly used and are used only in special applications where optimized use of storage is required.


| Operators | Meaning                  |
|-----------|--------------------------|
| `<<`      | Shift bits left          |
| `>>`      | Shift bits right         |
| `~`       | Bitwise inversion (one’s complement)             |
| `&`       | Bitwise AND              |
| `\|`       | Bitwise OR               |
| `^`       | Bitwise XOR              |

---

### 💻 Code Example:
```python
print(5 << 1); # 10
print(5 >> 1); # 2
```

---

## 🧮 Membership Operators

- The membership operators are useful to test for membership in a sequence such as string, lists, tuples and dictionaries. 
- There are two type of Membership operator:- **`in`, `not in`**

### `in` 

- This operators is used to find an element in the specified sequence. 
- It returns `True` if element is found in the specified sequence else it returns `False`.
### 💻 Code Example:
```python
st1 = "Welcome top my app"
print("to" in st1) # True

st3 = "Welcome to geekyshows"
print("subs" in st3) # False
```
### `not in`

- This operators works in reverse manner for `in` operator. 
- It returns `True` if element is not found in the specified sequence and if element is found, then it returns `False`.

### 💻 Code Example:
```python
st1 = "Welcome top my app"
print("to" not in st1) # False

st3 = "Welcome to geekyshows"
print("subs" not in st3) # True
```

## 🧮 Identity Operators

- The identity operators compare the memory locations of two objects. Hence, it is possible to know whether two objects are same or not. 
- There are two types of Identity operator:- **`is`, `is not`**

### `is` 

- This operator `is` used to compare whether two objects are same or not.  
- It returns `True` if memory location of two objects are same else it returns `False`.
Ex:- 
a = 10
b = 10


### 💻 Code Example:
```python
a=10
b=10
print(a is b) # True
a=10
b='10'
print(a is b) # False
```
### `is not`

- This operator works in reverse manner for `is` operator. 
- It returns `True` if memory location of two objects are not same and if they are same it returns `False`.

### 💻 Code Example:
```python
a=10
b=10
print(a is b) # False
a=10
b='10'
print(a is b) # True
```
## 📊Operator Precedence and Associativity

The computer scans an expression which contains the operators from left to right and performs only one operation at a time. The expression will be scanned many times to produce the result. The order in which various operations are performed is known as hierarchy of operations or operator precedence. Some of the operators of the same level of precedence are evaluated from left to right or right to left. This is referred to associativity.

<div style="background-color: #f5f5dc; display: inline-block; padding: 10px;">
  <img src="/9_Operators/image.png" alt="Operator Precedence Table" style="display: block;">
</div>
