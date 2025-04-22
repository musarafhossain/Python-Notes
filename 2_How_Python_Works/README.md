# 2. How Python Works?

- ##  Byte Code
    - Byte Code represents the fixed set of instruction created by Python developers representing all type of operations like arithmetic operations, comparison operation, memory related operation etc. 
    
    - The size of each byte code instruction is 1 byte or 8 bits. 
    - We can find byte code instruction in the .pyc file.
    
- ## Python Compiler
    - A Python Compiler converts the program source code into byte code.
    
    - **Type of Python Compilers** :-
        - CPython
        - Jpython/ Jython
        - PyPy
        - RubyPython
        - IronPython
        - StacklessPython
        - Pythonxy
        - AnacondaPython

- ## How Python Code is Executed (Step-by-Step)

    - Write Source Code / Program
    - Compile the Program using Python Compiler
    - Compiler Converts the Python Program into byte Code
    - Computer/Machine Can not understand Byte Code so we convert it into Machine Code using PVM
    - PVM uses an interpreter which understands the byte code and convert it into machine code
    - Machine Code instructions are then executed by the processor and results are displayed

![Diagram](/2_How_Python_Works/image.png)
 
    