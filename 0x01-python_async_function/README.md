0x01-python_async_function
Description
This project focuses on asynchronous programming in Python using asyncio. It covers the fundamentals of async and await syntax, running concurrent coroutines, creating asyncio tasks, and measuring execution time. The goal is to gain a deep understanding of asynchronous execution in Python, including the use of the random module to introduce variability in coroutine execution times.

Learning Objectives
By the end of this project, you should be able to explain the following concepts without external references:

The async and await syntax.
How to execute an async program with asyncio.
How to run multiple coroutines concurrently.
How to create asyncio tasks.
How to use the random module in asynchronous code.
Requirements
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
Your code should follow the pycodestyle style (version 2.5.x).
All functions and coroutines must be type-annotated.
All modules and functions should include documentation explaining their purpose.
The first line of all your files should be exactly #!/usr/bin/env python3.
All files must be executable.
Files
0-basic_async_syntax.py: Contains a coroutine wait_random that waits for a random delay between 0 and max_delay seconds and returns the delay.
1-concurrent_coroutines.py: Contains an async routine wait_n that spawns wait_random n times with a specified max_delay and returns the list of delays in ascending order.
2-measure_runtime.py: Contains the measure_time function that calculates the total execution time for running wait_n and returns the average time per coroutine.
3-tasks.py: Contains a function task_wait_random that creates and returns an asyncio.Task for wait_random.
4-tasks.py: Contains the task_wait_n function, an altered version of wait_n that uses task_wait_random to schedule the coroutines.
