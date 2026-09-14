# Practice 3: Python Functions and Object-Oriented Programming

## Overview

This practice focuses on mastering Python functions, lambda expressions, and object-oriented programming (OOP) concepts. You'll learn to create reusable code, perform quick operations with lambdas, and build classes with inheritance.

## Learning Objectives

By the end of this practice, you should be able to:
- Define and use functions with various argument types
- Apply lambda functions with built-in functions like `map()`, `filter()`, and `sorted()`
- Create classes, objects, and methods
- Implement inheritance and method overriding
- Organize code in a proper project structure

---

## Tasks

### Task 1: Learn Python Functions

**Resource**: [W3Schools Python Functions Tutorial](https://www.w3schools.com/python/python_functions.asp)

**Topics to Master**:
- Function definition and calling
- Function arguments (positional, default, *args, **kwargs)
- Return values and statements
- Passing lists and other data types as arguments
- Function documentation with docstrings

**Requirements**:
- Read all sections and complete interactive exercises on W3Schools
- Create at least 4 practical examples showing different function concepts
- Add clear comments explaining each example

### Task 2: Learn Python Lambda Expressions

**Resource**: [W3Schools Python Lambda Tutorial](https://www.w3schools.com/python/python_lambda.asp)

**Topics to Master**:
- Lambda syntax and basic usage
- Using lambda with `map()` for transformation
- Using lambda with `filter()` for selection
- Using lambda with `sorted()` for custom sorting
- Anonymous functions vs regular functions

**Requirements**:
- Complete all W3Schools exercises
- Create at least 4 examples demonstrating lambda usage
- Show practical applications of each lambda pattern

### Task 3: Learn Python Classes and Objects

**Resource**: [W3Schools Python Classes Tutorial](https://www.w3schools.com/python/python_classes.asp)

**Topics to Master**:
- Class definition and object creation
- The `__init__()` constructor method
- Instance methods and the `self` parameter
- Class variables vs instance variables
- Modifying and deleting object properties

**Requirements**:
- Study all class concepts on W3Schools
- Create at least 4 examples showing different OOP features
- Demonstrate class vs instance variable differences

### Task 4: Learn Python Inheritance

**Resource**: [W3Schools Python Inheritance](https://www.w3schools.com/python/python_inheritance.asp)

**Topics to Master**:
- Parent and child class relationships
- Using `super()` to call parent methods
- Method overriding
- Multiple inheritance
- Abstract base classes (optional advanced topic)

**Requirements**:
- Read inheritance tutorials
- Create at least 4 examples showing inheritance patterns
- Include examples of method overriding and `super()` usage

### Task 5: Create and Organize Code Examples

**Project Structure**:
Create the following directory structure in your repository:

```
Practice-03/
├── functions/
│   ├── basic_functions.py
│   ├── function_arguments.py
│   ├── return_values.py
│   └── args_kwargs.py
├── lambda/
│   ├── lambda_basics.py
│   ├── lambda_with_map.py
│   ├── lambda_with_filter.py
│   └── lambda_with_sorted.py
├── classes/
│   ├── class_definition.py
│   ├── init_method.py
│   ├── class_methods.py
│   └── class_variables.py
├── inheritance/
│   ├── inheritance_basics.py
│   ├── super_function.py
│   ├── method_overriding.py
│   └── multiple_inheritance.py
└── README.md (this file)
```
---

##  Problem Set

Solve programming problems to apply your knowledge:

Open the **Practice-Tasks-Set** files, add solve all the problems there.

---

**Code Requirements**:
- Each `.py` file should contain practical, working examples
- Include comments explaining what each code block does. Start the comments with word "Here is".
- Use descriptive variable names. 
- Test all code to ensure it runs without errors

**GitHub Submission**:
```bash
# Stage all files
git add .

# Commit with descriptive message
git commit -m "Complete Practice 3: Python functions, lambda, classes, and inheritance examples"

# Push to main branch
git push origin main
```

---

**Deadline**: Check MS Teams for the submission deadline.



## Troubleshooting Guide

### Common Issues and Solutions

**"Function not defined" errors**:
- Check function name spelling and parentheses
- Ensure function is defined before it's called
- Test functions individually

**Lambda syntax errors**:
- Remember: `lambda arguments: expression`
- No `return` statement needed in lambda
- Test lambda expressions separately

**Class instantiation problems**:
- Verify `__init__` method signature matches object creation
- Check `self` parameter usage in methods

**Inheritance issues**:
- Ensure parent class is imported or defined first
- Use `super()` correctly for parent method calls

**General debugging**:
- Add `print()` statements to trace execution
- Use Python's built-in `help()` function for documentation
- Ask questions during practice sessions or office hours

### Additional Resources

- 📖 [Python Official Documentation](https://docs.python.org/3/)
- 🎥 [Corey Schafer OOP Playlist](https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc)
- 🛠️ [Python Tutor Visualizer](http://pythontutor.com/) - Visualize code execution

---

## Assessment Criteria

Your practice will be evaluated based on:
- Code correctness and functionality
- Proper use of Python concepts
- Code organization and documentation
- GitHub repository structure
- Completion of online problem set
- Adherence to submission deadlines