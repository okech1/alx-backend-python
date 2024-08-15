# Python - Variable Annotations

## Description

This project is part of the **ALX Backend Python** curriculum. The main focus is to understand and apply Python's type annotations introduced in Python 3.5. Type annotations allow developers to specify the expected data types of function arguments and return values, which helps in code readability and debugging. Additionally, this project touches on the concept of duck typing and how to use `mypy` to validate the types in your Python code.

## Learning Objectives

By the end of this project, you should be able to:

- Understand type annotations in Python 3.
- Use type annotations to specify function signatures and variable types.
- Apply duck typing in Python.
- Validate your Python code using `mypy`.

## Requirements

- Python 3.7
- Ubuntu 18.04 LTS
- All files are executable and follow the pycodestyle (version 2.5) style guide.

## Files

- **0-add.py**: Contains a function `add(a: float, b: float) -> float` that returns the sum of two floats.
- **1-concat.py**: Contains a function `concat(str1: str, str2: str) -> str` that concatenates two strings.
- **2-floor.py**: Contains a function `floor(n: float) -> int` that returns the floor value of a float.
- **3-to_str.py**: Contains a function `to_str(n: float) -> str` that returns the string representation of a float.
- **4-define_variables.py**: Defines and annotates variables with specified values.
- **5-sum_list.py**: Contains a function `sum_list(input_list: List[float]) -> float` that returns the sum of a list of floats.
- **6-sum_mixed_list.py**: Contains a function `sum_mixed_list(mxd_lst: List[Union[int, float]]) -> float` that returns the sum of a list containing both integers and floats.
- **7-to_kv.py**: Contains a function `to_kv(k: str, v: Union[int, float]) -> Tuple[str, float]` that returns a tuple where the first element is a string and the second is the square of an int/float.
- **8-make_multiplier.py**: Contains a function `make_multiplier(multiplier: float) -> Callable[[float], float]` that returns a function that multiplies a float by a given multiplier.
- **9-element_length.py**: Contains a function `element_length(lst: Iterable[Sequence]) -> List[Tuple[Sequence, int]]` that returns a list of tuples containing elements and their lengths.

## Usage

To run the Python files, you need to have Python 3.7 installed on your machine. Make sure each script is executable by using the command:

```bash
chmod +x filename.py
