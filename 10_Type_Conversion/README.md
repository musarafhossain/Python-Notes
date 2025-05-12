# Type Conversion

- Converting one data type into another data type is called `Type Conversion`. 
- Type of Type Conversion:-
    - #### Implicit Type Conversion 
    - #### Explicit Type Conversion

## Implicit Type Conversion 

- In the Implicit type conversion, python automatically converts one data type into another data type.
- #### Example :-
```python
a = 5
b = 2
value = a / b
print(value)       # 2.5
print(type(value)) # <class 'float'>
```

## Explicit Type Conversion 

- In the Cast/Explicit Type Conversion, Programmer converts one data type into another data type.
`- int(n)`
`- float(n)`
`- complex(n)` 
`- complex(x, y), where x is real part and y is imaginary part`
`- str(n)`
`- list(n)`
`- tuple(n)`
`- bin(n)`
`- oct(n)`
`- hex(n)`
- #### Example :-

```python
a = 5
value = bin(a)
print(value)              # 0b101
print(type(value))        # <class 'str'>
print(complex(5,7))       # (5+7j)
print(type(complex(5,7))) # <class 'complex'>
```
