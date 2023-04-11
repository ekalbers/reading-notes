# Ten Thousand Game 2

## Reading
### [List Comprehensions](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

## Audio
### [Debugging with PySnooper](https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/)

## Bookmark and Review
### [Primer on Decorators](https://realpython.com/primer-on-python-decorators/)

## Reading Questions
1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
    - You put a list comprehension statement within braces, sos x = [statement]
    - x = [1, 2, 3]    y = [i*i for i in x]
2. What is a decorator in Python?
    - it is essentially wrapping one function in another function to modify the behavior of the function
3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
    - The concept of decorators is that you pass a function a different fucntion as a parameter so that function 1 can use the function it was passed within itself.
   ~~~python
   def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

    def say_whee():
        print("Whee!")
    
    say_whee = my_decorator(say_whee)
   ~~~
