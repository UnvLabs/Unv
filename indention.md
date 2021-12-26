## Indentation

Indentation refers to the spaces at the beginning of a code line.

Where in other programming languages the indentation in code is for readability only, the indentation in Unv is very important.

Unv uses indentation to indicate a block of code like Python.

Its a syntax error if you skip the indentation:
```py
if  5  >  2
print("Five is greater than two!")
```
```diff
- It's a Syntax Error
```

You have to use the same number of spaces in the same block of code.
```py
if  5  >  2
  print("Five is greater than two!")  
if  5  >  2
    print("Five is greater than two!")
```
```diff
- It's a Syntax Error
```

The number of spaces is up to you as a programmer, but it has to be at least one.
```py
if  5  >  2
 print("Five is greater than two!")  
if  5  >  2
 print("Five is greater than two!")
```
```diff
! It's a Correct. But ugly.
```
4 spaces is recommended for indention
```py
if  5  >  2
    print("Five is greater than two!")  
if  5  >  2
    print("Five is greater than two!")
```
```diff
+ It's a Correct. And beautiful.
```
