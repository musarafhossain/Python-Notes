# 7. Varibale

- In C, Java or some other programming languages, a variable is an identifier or a name, connected to memory location.

![Diagram](/7_Variable/image1.png)

- In Python, a variable is considered as tag that is tied to some value. Python considers value as objects. 

![Diagram](/7_Variable/image2.png)
![Diagram](/7_Variable/image3.png)

- **Rules:-** 
    - Every variable name should start with alphabets or underscore `_`.
    
    - No spaces are allowed in variable declaration.
    
    - Except underscore `_` no other special symbol are allowed in the middle of the variable declaration
    
    - A variable is written with a combination of letters, numbers and special characters `_` (underscore)
    
    - No Reserved keyword
    
- **Examples:-**

|     Do    |   Don't   |
|-----------|-----------|
| A         |    and    |
| a         |   15name  |
| name      |   $city   |
| name15    | Full$name |
| _city     | Full Name |
| Full_name |           |
| FullName  |           |

Code:-
```python
a = 10
b = a
a = 20 
print(a, b)
```
Output:
```bash
20 10
```
