# Escape Sequence

- Escape sequences are control character used to move the cursor and print characters such as `'`, `"`. `\` and so on.

| Escape Sequence | Meaning |
|-----------------|---------|
| `\\` | Backslash
| `\'` | Single Quote
| `\"` | Double Quote
| `\a` | Bell
| `\b` | Backspace
| `\f` | Formfeed
| `\n` | NewLine
| `\r` | Carriage Return
| `\t` | Horizontal Tab
| `\v` | Vertical Tab
| `\newline` | Backslash and NewLine Ignored

#### Example
```python
print("Hello World\"s")
print('Hello World\'s')
print('Hello World\\s')
print("Hello World\bs")
print("Hello World\ts")
```
#### Output
```bash
Hello World"s
Hello World's
Hello World\s
Hello Worls
Hello World    s
```