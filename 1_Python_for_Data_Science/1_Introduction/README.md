# Why to learn python?
(not c/c++/Java ?)

- Very simple language to learn.
- Best packages for AI such as matplotlib, numpy, scipy, scikit-learn, Tensorflow, etc.,
- iPython Notebook for interactive data analysis and modelling
- Extensively used in the industry.

# Python Keywords

- Keywords are the reserved words in python

- We can't use a keyword as variable name, function name or any other identifier

- Keywords are case sentive

```Python
#Get all keywords

import keyword

print(keyword.kwlist)

print("Total number of keywords ", len(keyword.kwlist))
```
# Identifiers

Identifier is the name given to entities like class, functions, variables etc. in Python. It helps differentiating one entity from another.

### Rules for Writing Identifiers:

1. Identifiers can be a combination of letters in lowercase (a to z) or uppercase (A to Z) or digits (0 to 9) or an underscore (_).

2. An identifier cannot start with a digit. 1variable is invalid, but variable1 is perfectly fine.

3. Keywords cannot be used as identifiers.

example : 
```python
global = 1

"""
File "<ipython-input-3-d0026cf49b71>", line 1
    global = 1
           ^
SyntaxError: invalid syntax
"""
```
 We cannot use special symbols like !, @, #, $, % etc. in our identifier.

```python
a@ = 10             #can't use special symbols as an identifier

"""
  File "<ipython-input-5-b512271f00c8>", line 1
    a@ = 10             #can't use special symbols as an identifier
     ^
SyntaxError: invalid syntax
"""
```