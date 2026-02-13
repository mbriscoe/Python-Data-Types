# 🐍 Python Data Types Guide

A comprehensive Jupyter notebook guide covering all fundamental Python data types with practical examples and detailed explanations.

## 📋 Overview

This educational resource provides an in-depth exploration of Python's core data types, designed for data analysis students and Python beginners. Each data type is explained with code examples, summaries, and practical use cases.

## 📚 Topics Covered

### 1. **Numeric Data Types**

- **Integer (`int`)**: Whole numbers with unlimited precision
- **Float (`float`)**: Decimal numbers with 64-bit double precision
- **Complex (`complex`)**: Numbers with real and imaginary components
- Arithmetic operations and conversions

### 2. **String Data Type**

- String creation (single, double, and triple quotes)
- Immutability and indexing
- Slicing syntax `[start:end:step]`
- Common string methods (`.upper()`, `.lower()`, `.split()`, `.replace()`, etc.)
- String formatting with f-strings

### 3. **Boolean Data Type**

- `True` and `False` values
- Boolean operators (`and`, `or`, `not`)
- Comparison operators
- Truthiness and falsy values in Python
- Use in control flow and conditional expressions

### 4. **List Data Type**

- Ordered, mutable collections
- Adding, removing, and modifying elements
- List slicing and indexing
- List comprehensions
- Common methods (`.append()`, `.insert()`, `.remove()`, `.pop()`, etc.)

### 5. **Tuple Data Type**

- Ordered, immutable collections
- Tuple unpacking and multiple assignment
- When to use tuples vs lists
- Performance benefits
- Limited methods (`.count()`, `.index()`)

### 6. **Dictionary Data Type**

- Key-value pair mappings
- Fast lookups and modifications
- Dictionary methods (`.get()`, `.keys()`, `.values()`, `.items()`)
- Dictionary comprehensions
- Nested dictionaries
- Use cases (configuration, JSON data, caching)

### 7. **Set Data Type**

- Unordered collections of unique elements
- Automatic duplicate removal
- Mathematical set operations (union, intersection, difference)
- Fast membership testing
- Common methods (`.add()`, `.remove()`, `.discard()`)

### 8. **Type Conversion**

- Converting between data types (`int()`, `float()`, `str()`, etc.)
- String to number conversions
- Collection conversions (list ↔ tuple ↔ set)
- Handling conversion errors with try-except
- Best practices for validating conversions

### 9. **Checking Data Types**

- Using `type()` to get object types
- Using `isinstance()` for type validation
- Checking multiple types at once
- Practical usage in conditional statements
- Type checking best practices

## 📊 Quick Reference Table

| Data Type | Mutable | Ordered | Duplicates | Example     |
| --------- | ------- | ------- | ---------- | ----------- |
| **int**   | No      | N/A     | N/A        | `42`        |
| **float** | No      | N/A     | N/A        | `3.14`      |
| **str**   | No      | Yes     | Yes        | `"hello"`   |
| **bool**  | No      | N/A     | N/A        | `True`      |
| **list**  | Yes     | Yes     | Yes        | `[1, 2, 3]` |
| **tuple** | No      | Yes     | Yes        | `(1, 2, 3)` |
| **dict**  | Yes     | Yes\*   | No (keys)  | `{'a': 1}`  |
| **set**   | Yes     | No      | No         | `{1, 2, 3}` |

\*Insertion order preserved since Python 3.7

## 🎯 Choosing the Right Data Type

- **Need to modify data?** → Use List, Dictionary, or Set
- **Data shouldn't change?** → Use Tuple or String
- **Need key-value pairs?** → Use Dictionary
- **Need unique values only?** → Use Set
- **Need ordered sequence?** → Use List or Tuple
- **Working with text?** → Use String

## 🚀 Getting Started

### Prerequisites

```bash
python 3.7+
jupyter notebook or jupyter lab
```

### Installation

1. Clone or download this repository
2. Install required packages (if any):
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook

```bash
jupyter notebook python_data_types.ipynb
```

or

```bash
jupyter lab python_data_types.ipynb
```

## 📖 How to Use This Guide

1. **Sequential Learning**: Work through each section in order for a complete understanding
2. **Run All Code Cells**: Execute each code example to see live results
3. **Experiment**: Modify the code examples to test your understanding
4. **Review Summaries**: Each section includes a collapsible summary of key points
5. **Reference**: Use the quick reference table for a fast lookup

## 💡 Key Learning Outcomes

After completing this notebook, you will be able to:

- ✅ Understand all fundamental Python data types
- ✅ Choose the appropriate data type for different scenarios
- ✅ Perform operations and transformations on each data type
- ✅ Convert between different data types safely
- ✅ Validate and check data types in your code
- ✅ Apply best practices for working with Python data structures

## 🤝 Contributing

Feel free to suggest improvements or report issues. This is an educational resource meant to help learners understand Python data types thoroughly.

## 📄 License

This notebook is provided for educational purposes.

---

**Happy Coding! 🐍✨**

---

## 👨‍🏫 Created By

<div align="center">

![Code Institute Logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

**Mark Briscoe**  
Code Institute

📧 [mark.briscoe@codeinstitute.net](mailto:mark.briscoe@codeinstitute.net)

</div>
