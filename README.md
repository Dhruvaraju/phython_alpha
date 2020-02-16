# python3_alpha
Learning log for python from a networking perspective

### python
- A scripting language, which can be used for automating tasks
- Extension of python program files is ```.py```.
- Python installation will give an ide called as idle which can be used to run a python program.
- to check if python is installed in your machine, type in the word __python__ in command prompt. it will show the version of python installed.

### First program
- python uses functions to perform operations.
- ```print``` is used to print a line to console. ``` print ('Console is active'); ```
- To take user input you can use a function called input. ``` var1 = input('Enter your name : ');```
- To execute a python script in windows command prompt, use ```python <<filename with entire path>>```
``` python c:/folder1/myapp.py ```

### Variables
- Should start with an alphabet, should not contain space.
- variables starting with '_' and '__' are python reserved keywords should not use them for your programs.
- variables can be assigned in many ways
```python
    var = "testdata" // assigning string to var
    a = 5 // assigning 5 to variable a
    a=b=c= 10 // assigning the variables a,b,c to 10
    a,b,c = 1,2,3 // assigning multiple variable at once, a to 1, b to 2, c to 3
```
- function id is used to get the memory location of an attribute. example id(a) will give the memory location of a.

### Data-types in python
- The following are the data types in python
    - strings
    - numbers
    - booleans
    - lists
    - sets
    - frozensets
    - tuples
    - ranges
    - dictionaries
    - None
- Few are mutable (lists, dictionaries, sets), these can be modified after creation and few are immutable (Strings, numbers, tuples and frozensets) these cannot be modified after creation.

### Strings
- A sequence of characters, python uses index to identify each character.
- index start from left from 0 and -1 from right.
- Some of the string operations are performed in main.py