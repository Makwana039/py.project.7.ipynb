# Multi-Utility Toolkit

A beginner-friendly Python project that combines multiple utilities into one menu-driven application. It uses Python's built-in modules to perform date and time calculations, mathematical operations, random data generation, UUID creation, file handling, and module exploration.

## Project Overview

The Multi-Utility Toolkit is designed to practice Python programming concepts through a collection of useful tools. Users can select an operation from the main menu and navigate between different utility sections.

## Features

### 1. Date and Time Operations

* Display the current date and time.
* Calculate the difference between two dates.
* Format dates in different styles.
* Measure elapsed time using a stopwatch.
* Run a countdown timer.

### 2. Mathematical Operations

* Perform addition, subtraction, multiplication, and division.
* Calculate trigonometric values such as sine, cosine, and tangent.
* Calculate the factorial of a non-negative integer.
* Calculate natural and base-10 logarithms.
* Calculate compound interest.
* Find the area of a circle.

### 3. Random Data Generation

* Generate a random number within a specified range.
* Generate a list of random numbers.
* Generate a random password using Python's `secrets` module.
* Select random items from a collection.
* Generate a six-digit demonstration OTP.

### 4. UUID Generation

* Generate a unique identifier using UUID version 4.
* Generate multiple UUIDs.
* Control the number of UUIDs generated.

### 5. File Operations

* Create and write text files.
* Read existing text files.
* Append new content to files.
* Find and replace text.
* Store project files in a dedicated `data` directory.

### 6. Dynamic Module Exploration

* Explore built-in Python modules.
* Display module attributes using the `dir()` function.
* Explore modules such as `datetime`, `time`, `math`, `random`, `uuid`, `secrets`, and `string`.

## Technologies Used

* **Language:** Python
* **Modules:** `datetime`, `time`, `math`, `random`, `uuid`, `secrets`, `string`, `pathlib`
* **Concepts:** Functions, loops, conditional statements, exception handling, modules, file handling, user input, and menu-driven programming.

## Requirements

* Python 3.8 or later recommended.
* A code editor such as Visual Studio Code, PyCharm, or IDLE.
* No external Python packages are required.

## Installation

1. Clone or download this repository.

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder in your code editor.

3. Ensure Python is installed on your computer.

4. Open a terminal in the project directory.

## How to Run

Run the main Python file:

```bash
python main.py
```

Replace `main.py` with the actual filename if your main program uses a different name.

## Main Menu

The application provides the following options:

| Option | Operation                           |
| ------ | ----------------------------------- |
| 1      | Datetime and Time Operations        |
| 2      | Mathematical Operations             |
| 3      | Random Data Generation              |
| 4      | Generate Unique Identifiers (UUID)  |
| 5      | File Operations                     |
| 6      | Explore Module Attributes (`dir()`) |
| 7      | Exit                                |

Select an option by entering its corresponding number. Follow the on-screen prompts to complete the operation.

## Project Structure

A recommended structure for this project is:

```text
Multi-Utility-Toolkit/
│
├── main.py
├── utilities/
│   ├── __init__.py
│   ├── datetime_utils.py
│   ├── math_utils.py
│   ├── random_utils.py
│   ├── uuid_utils.py
│   └── file_utils.py
│
├── data/
│   └── report.txt
│
└── README.md
```

**Note:** The structure above represents the modular version of the project. If all functions are currently in one Python file, keep that file as the main program or separate the functions into the suggested modules and import them into `main.py`.

The `data` directory is created automatically by the program if it does not already exist. The example `report.txt` file is optional.

## Python Concepts Practiced

| Concept                | Purpose                                    |
| ---------------------- | ------------------------------------------ |
| Functions              | Organize operations into reusable blocks   |
| Modules and imports    | Reuse Python's built-in functionality      |
| Conditional statements | Process menu selections                    |
| Loops                  | Keep menus running until the user exits    |
| Exception handling     | Handle invalid input and file errors       |
| `datetime`             | Work with dates and times                  |
| `math`                 | Perform mathematical calculations          |
| `random`               | Generate random numbers and samples        |
| `secrets`              | Generate security-oriented random values   |
| `uuid`                 | Create unique identifiers                  |
| `pathlib`              | Manage file paths                          |
| File handling          | Read, write, append, and update text files |
| `dir()`                | Inspect module attributes                  |

## Input Validation and Error Handling

The project includes validation to help handle common errors, including:

* Invalid numeric input.
* Incorrect date or time formats.
* Negative values where they are not allowed.
* Invalid menu selections.
* Invalid file names and missing files.
* Invalid ranges and sample sizes.

## Learning Outcomes

By completing this project, you can practice:

* Writing modular and reusable Python code.
* Working with built-in libraries.
* Building interactive, menu-driven applications.
* Performing mathematical and date/time calculations.
* Handling text files safely.
* Validating user input and handling exceptions.
* Exploring Python modules and their attributes.

## Future Improvements

* Add a graphical user interface using Tkinter.
* Add calculation history.
* Add more unit conversions and geometric shapes.
* Add automated tests for utility functions.
* Improve password generation by guaranteeing a mix of character types.
* Add logging and more detailed error messages.

## Author
Python Project — Multi-Utility Toolkit

Created as a learning project to practice Python programming, modular design, and standard library utilities.

## License

This project is intended for educational and practice purposes. You may adapt it for personal learning and portfolio development.
