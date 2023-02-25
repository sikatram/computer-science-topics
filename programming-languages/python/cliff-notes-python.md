# Python Sparknote

Here is a list of non-trivial things I've learned that I have found to be helpful

---

## Formatting

**Indentation**: The number of spaces is up to you as a programmer, the most common use is four, but it has to be at least one.

---

## Commenting

Comments can be placed at the end of a line, and Python will ignore the rest of the line:

```python
print("Hello, World!") #This is a comment
```

You can use a multiline string to comment out multiple lines of code. Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it:

```python
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```

As long as the string is not assigned to a variable, Python will read the code, but then ignore it, and you have made a multiline comment.