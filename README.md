# Python Functions

![](https://res.cloudinary.com/ahonore42/image/upload/v1615581981/ga/Screen_Shot_2021-03-12_at_2.45.05_PM_rnhmr0.png)

## Overview
In this lesson, we'll be learning about python function syntax, how it uses indentation to separate blocks of code, return statements and arguments, along with how it compares with JavaScript function syntax.

## Objectives

- Learn Python function syntax
- Learn proper indentation for code blocks
- Practice returning values from functions
- Practice passing arguments/parameters to functions

## Getting Started
- `Fork` and `clone` this repository and `cd` into the directory

## Function Syntax

In javascript we declare functions like this:

```js
const myFunc = () => {
  return 'Hi'
}
```

Let's see how we declare functions in python:

```python
def my_func():
  return 'Hi'
```

As you can see, we first define a function using the `def` keyword, we set the name of the function as `my_func` and add a set of parentheses, `()`, notice the `:` symbol. In python we use the `:` to define a block of code.

One important thing to note here, Python is very strict on indentation, you can either use `1 tab` or `2 spaces` to indent your code. Indentation is how python read's blocks of code.

## Function Arguments/Parameters

We can also pass in arguments and define parameters in Python functions by creating a variable in the parentheses, example:

```python
def sum_func(num):
  return num
```

`Num` works as a placeholder to let our function know that it will receive something to perform a calculation on.

To invoke functions, it follows the same pattern as most programming languages, Example:

```js
const myFunc = () => {
  console.log('Hi)
}
myFunc()
// Prints Hi To The Console
```

```python
myFunc():
  print('Hi')

myFunc()
# Prints hi to the console
```

## Putting Functions To Use

Follow the directions in `main.py` to complete this lab.

Test your code using `python3 func_test.py` , you should have 5 passing tests. Happy Coding!
