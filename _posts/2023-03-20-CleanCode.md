---
title: "(Tip) Clean code"
date: 2023-03-20
tags:
- Tip
- Coding
---

# These tips may help your code cleaner
I know there may more concise solutions for below examples in Python. Python can expresses complex idea in a single line of code.
I only use these examples to illustrate my statements. The ideas could be applied in other programming languages, i.e C/C++. 

## Avoid nested if-statements

Instead of doing this
```python
def classify(score):
    if score > 5:
        if score > 7:
            if score > 9:
                return "Excellent"
            else:
                return "Good"
        else:
            return "Passed"
    else:
        return "Failed"
    
```

Do this
```python
def classify(score):
    if score <= 5:
        return "Failed"
    
    if score <= 7:
        return "Passed"

    if score <= 9:
        return "Good"

    return "Excellent"
```

## Consider using a dictionary

Instead of doing this
```python
def convert(score):
    if score == "A":
        return 4

    if score == "B":
        return 3

    if score == "C":
        return 2

    if score == "D":
        return 1

    return -1
```

Do this
```python
def convert(score):
    char2num = {"A":4, "B":3, "C":2, "D":1}

    if score in char2num.keys():
        return char2num[score]

    return -1
```

## Consider avoiding using index in for loop

Instead of doing this
```python
def sum(numbers):
    s = 0
    for i in range(len(numbers)):
        s += numbers[i]
```

Do this
```python
def sum(numbers):
    s = 0
    for number in numbers:
        s += number
```
