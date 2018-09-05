# Python Basics

## Installation and Setup

We will use `python 3`. 


Run the following command in command prompt to check if Python 3 is already installed :

```shell
python3
```

You should see the following:
Python 3.6.3 (v3.4.3:9b73f1c3e601, Feb 23 2015, 02:52:03)

If you don't,  lets install python:
Download the installer from the given link:
[https://www.python.org/ftp/python/3.6.3/python-3.6.3-amd64.exe](https://www.python.org/ftp/python/3.6.3/python-3.6.3-amd64.exe)

Enable the “Add Python 3.6 to PATH” option and then click “Install Now.”

Run the command python -V to check the version

```shell
python -v
```



## Variables and its types

Python doesn't have a strong-type

```python
x = 1
y = 2
x + y
```

Different type of variable in Python

```python
name = "Youstart Labs"
age = 4
ratings = 4.9
money = None
fruits = ['mango', 'apple', 'watermelon']

```

You can check the data type using `type` function

```python
type(name)
```

## Basic Operators

```python
a = 5
b = 6
print(a+b)
# 11
print(a*b)
# 30
print(a-b)
# -1
print(a/b)
# 0.8333333333333334
print(5%6)
# 5


```

## Conditional Statement

```python
a = 2

if a==3:
    print("ok")
elif a<5:
    print(a)
else:
    print("not ok")

```

## Loops

```python
fruits = ['mango', 'apple', 'watermelon']

for fruit in fruits:
    print(fruit)
```

## Functions

functions in python are defined by `def`

```python
def add(x, y):
    return x + y

add(5,6)
# 30
```
