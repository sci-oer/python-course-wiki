# Introduction to Writing Functions in Python 3

As you start to write more complex programs, you will find that you are writing the same code over and over again. This can lead to messy and difficult-to-read code. To make your code more organized and easier to maintain, you can use functions.

A function is a block of code that performs a specific task. You can call this code multiple times from different parts of your program. This allows you to reuse code and avoid writing the same code over and over again.

In Python, you can define a function using the `def` keyword. You then give the function a name, and specify the input parameters in parentheses. The body of the function is indented below the function definition. When you call the function, any input parameters are passed in, and the function returns a result (if any).

Here are a couple of examples of simple functions:

```python
def add_numbers(a, b):
    return a + b

def multiply_numbers(a, b):
    return a * b
```

In this example, the first function is called `add_numbers`. It takes two input parameters `a` and `b`, and returns their sum. The second function is called `multiply_numbers`. It takes two input parameters `a` and `b`, and returns their product.

You can call these functions multiple times with different values for `a` and `b`, like this:

```python
sum_result = add_numbers(2, 3)
product_result = multiply_numbers(4, 5)
```

In this example, `sum_result` will be `5` (the sum of 2 and 3), and `product_result` will be `20` (the product of 4 and 5).

Functions can be a powerful tool in your programming arsenal. They can make your code more modular, easier to read, and simpler to debug. With a good understanding of functions, you'll be well on your way to writing more advanced programs in Python.