---
reading: '[PY4E: Conditionals](https://www.py4e.com/html3/03-conditionals)'
...

Conditional Execution
=====================

Control Flow
------------

- By default, the Python interpreter runs the next instruction in our program
- In order to create more complex programs, it is helpful to choose which instruction runs next
- This is modification of the control plane of program execution

if statement
------------

- Conditionally runs a block of code
- A Boolean expression (the *condition*) follows the if statement
- The `if` statement is terminated by a `:`

```python
if i == 0:
```

Example
-------

```python
if x > 0:
    print('x is positive')
```

---

![`if` control flow diagram](https://www.py4e.com/images/if.svg){height=540px}

Compound Statements
------------------

- Statements may be grouped together into blocks
- Blocks of statements should be indented using 4 spaces

Example
-------

```python
if False == True:
    print("This will not print")
    print("This will also not print")

print("This will print")
```

Else
----

- We may want to run something else when the `if` check fails
- This can be accomplished using `else`

---

![else control flow diagram](https://www.py4e.com/images/if-else.svg){height=540px}

Example
-------

```python
small_num = input("Enter a number:")
big_num = input("Enter a bigger number:")

if small_num < big_num:
    print("You entered the numbers correctly")
else:
    print("Your second number is too small")
```

Chained Conditionals
--------------------

- We may want more than two branches of execution
- We can chain multiple conditionals to achieve this

Chained Conditionals
--------------------

```python
if x < y:
    print('x is less than y')
elif x > y:
    print('x is greater than y')
else:
    print('x and y are equal')
```

---

![elif control flow diagram](https://www.py4e.com/images/elif.svg){height=540px}

Improved printing
-----------------

- The print function will accept multiple items to print
- Items must be separated by commas

Print Example
-------------

```python
print("Hello world!")
print("A few numbers: ", 1, 2, 3)
```

Printing a name
---------------

```python
name = input("What is your name?")
print("Hello", name)
```

Basic string operations
-----------------------

- Concatenation can be performed using the `+` operator
- Duplication can be performed using the `*` operator
- Comparison can be performed using standard comparison operators

Example
-------

```python
word1 = input("Enter a word:")
word2 = input("Enter another word:")

if word1 < word2:
    print(word1, "comes before", word2, "alphabetically")
elif word1 > word2:
    print(word1, "comes after", word2, "alphabetically")
else:
    print(word1, "and", word2, "are the same word")
```
