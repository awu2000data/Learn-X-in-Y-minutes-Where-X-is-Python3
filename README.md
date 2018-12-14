# Learn X in Y minutes (Where X=python3)
**Source:** [Learn X in Y minutes (Where X=python3) — Louie Dinh](https://learnxinyminutes.com/docs/python3/)
## 0. Comments
* **Single line comments**
```python
# Single line comments start with a number symbol.
```
* **Multi-line comments**
```python
""" 
Multiline strings can be written
using three "s, and are often used
as documentation.
"""
```
## 1. Primitive Datatypes and Operators
* **You have numbers**
```
3  # => 3
```
* **Math is what you would expect**
```python
1 + 1   # => 2
8 - 1   # => 7
10 * 2  # => 20
35 / 5  # => 7.0
```
* **Result of integer division truncated down both for positive and negative.**
```python
5 // 3       # => 1
5.0 // 3.0   # => 1.0 # works on floats too
-5 // 3      # => -2
-5.0 // 3.0  # => -2.0
```
*  **The result of division is always a float**
```python
10.0 / 3  # => 3.3333333333333335
```
* **Modulo operation**
```python
7 % 3  # => 1
```
* **Exponentiation (x**y, x to the yth power)**
```python
2**3  # => 8
```
* **Enforce precedence with parentheses**
```python
(1 + 3) * 2  # => 8
```
* **Boolean values are primitives (Note: the capitalization)**
```python
True
False
```
* **Negate with not**
```python
not True   # => False
not False  # => True
```
* **Boolean Operators**
**Note "and" and "or" are case-sensitive**
```python
True and False  # => False
False or True   # => True
```
* **True and False are actually 1 and 0 but with different keywords**
```python
True + True # => 2
True * 8    # => 8
False - 5   # => -5
```
