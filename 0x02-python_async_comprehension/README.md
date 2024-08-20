0x02. Python - Async Comprehension
Description
This project is focused on learning and implementing asynchronous comprehensions and generators in Python. The tasks involve creating asynchronous coroutines, using async comprehensions to handle asynchronous generators, and measuring the runtime of parallel asynchronous operations.

Learning Objectives
By the end of this project, you should be able to:

Write an asynchronous generator.
Use async comprehensions to work with asynchronous iterators.
Type-annotate generators in Python.
Measure and understand the runtime of asynchronous operations executed in parallel.
Requirements
Editor: vi, vim, emacs
Interpreter: Python 3.7 on Ubuntu 18.04 LTS
Style: Your code must adhere to the pycodestyle (version 2.5.x) standards.
Documentation:
Every module and function must have a docstring explaining its purpose.
Files should be formatted with a final newline character.
Files
0-async_generator.py: Contains the async_generator coroutine that yields random numbers between 0 and 10, one per second, over 10 iterations.
1-async_comprehension.py: Contains the async_comprehension coroutine that collects 10 random numbers using an async comprehension over async_generator.
2-measure_runtime.py: Contains the measure_runtime coroutine that runs async_comprehension four times in parallel using asyncio.gather and measures the total runtime.
