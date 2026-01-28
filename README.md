# Python Module Examples - SDGLA 3

## Introduction

This repository contains a structured collection of Python examples. The project demonstrates practical use of Python’s standard library alongside custom, user-defined modules, with a focus on clean code, modular design, and scalable project organization.

The repository serves as:

- A learning resource for Python modules and imports
- A reference for common standard library use cases
- A template for structuring small to medium-sized Python projects
- A foundation for more advanced, production-grade Python systems

---

## Project Structure

python_module_examples/
│
├── standard_library_examples/
│ ├── math_sqrt.py
│ ├── random_integer.py
│ ├── statistics_mean.py
│ ├── time_sleep.py
│ ├── os_listdir.py
│ ├── datetime_now.py
│ ├── random_shuffle.py
│ ├── math_trigonometry.py
│ ├── uuid_generate.py
│ └── calendar_month.py
│
├── user_defined_modules/
│ ├── greet/
│ │ ├── init.py
│ │ └── greet.py
│ ├── math_utils/
│ │ ├── init.py
│ │ └── math_utils.py
│ ├── string_utils/
│ │ ├── init.py
│ │ └── string_utils.py
│ └── conversion/
│ ├── init.py
│ └── conversion.py
│
└── main_scripts/
├── greet_main.py
├── math_utils_main.py
├── string_utils_main.py
└── conversion_main.py

---

## Repository Overview

The repository is divided into three logical sections:

- **standard_library_examples/**  
  Independent scripts demonstrating Python’s built-in modules.

- **user_defined_modules/**  
  Reusable custom modules organised as Python packages.

- **main_scripts/**  
  Executable scripts that import and use the custom modules.

This structure promotes separation of concerns, reusability, and maintainability.

---

## Standard Library Examples

Each script in `standard_library_examples/` can be executed independently.

| File | Module | Description |
|------|--------|-------------|
| `math_sqrt.py` | `math` | Computes square roots using `math.sqrt()` |
| `random_integer.py` | `random` | Generates random integers |
| `statistics_mean.py` | `statistics` | Calculates the arithmetic mean |
| `time_sleep.py` | `time` | Pauses execution |
| `os_listdir.py` | `os` | Lists directory contents |
| `datetime_now.py` | `datetime` | Retrieves the current date and time |
| `random_shuffle.py` | `random` | Shuffles a list in place |
| `math_trigonometry.py` | `math` | Computes trigonometric values |
| `uuid_generate.py` | `uuid` | Generates a UUID |
| `calendar_month.py` | `calendar` | Displays a formatted monthly calendar |

These scripts reflect common real-world tasks such as file handling, scheduling, numerical computation, and random sampling.

---

## User-Defined Modules

The `user_defined_modules/` directory contains reusable Python packages. Each subdirectory includes an `__init__.py` file to ensure correct package recognition and import resolution.

### Available Packages

#### greet

- `say_hello(name)`  
  Prints a greeting message.

#### math_utils

- `add(a, b)`  
  Returns the sum of two numbers.

#### string_utils

- `capitalize_word(word)`  
  Capitalizes the first character of a string.

#### conversion

- `celsius_to_fahrenheit(c)`  
  Converts a temperature value from Celsius to Fahrenheit.

These modules demonstrate modular programming and separation of concerns.

---

## Main Scripts

The `main_scripts/` directory contains entry-point scripts that demonstrate how to import and use the user-defined modules.

### Example Usage

``` from greet import greet
greet.say_hello("Alice")

from math_utils import math_utils
print(math_utils.add(10, 5))

from string_utils import string_utils
print(string_utils.capitalize_word("hello"))

from conversion import conversion
print(conversion.celsius_to_fahrenheit(30))
```
---

## Key Concepts Demonstrated
* Separation of concerns between examples, libraries, and application logic
* Effective use of Python’s standard library without external dependencies
* Modular design with user-defined packages
* Correct use of `__init__.py` for package imports
* Scalable project organization suitable for larger codebases

---

## Running the Examples
From the project root directory:
python standard_library_examples/math_sqrt.py
python main_scripts/greet_main.py
Scripts should be executed from the root directory to ensure imports resolve correctly.

---

## Intended Use
This repository may be used as:
* A learning resource for Python modules and imports
* A reference for standard library usage
* A template for structuring Python projects
* A foundation for more complex Python applications

---

## Disclaimer
The exercises and curriculum structure in this repository are based on training materials. This repository is shared for educational and portfolio purposes only.
