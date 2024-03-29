# 0x0A. Python - Inheritance
## Project Requirements
### Python Scripts
- Formatted with PEP8 style standards
- Compiled with `python3`
- All files must be executable
### Python Test Cases
- All test files must be inside `tests` folder
- All test files must be .txt files
- All test files must be executed using `python3 -m doctest ./tests/*`
- All modules should have a documentation `python3 -c 'print(__import__("my_module").__doc__)'`
- All your classes should have a documentation `(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`
- All functions should have a documentation `python3 -c 'print(__import__("my_module").my_function.__doc__)'`

## File Descriptions
**0-lookup.py:** a function that returns the list of available attributes and methods of an object

**1-my_list.py, tests/1-my_list.txt:** a class `MyList` that inherits from `list`

**2-is_same_class.py:** a function that returns True if the object is exactly an instance of the specified class ; otherwise False

**3-is_kind_of_class.py:** a function that returns True if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class ; otherwise False

**4-inherits_from.py:** a function that returns True if the object is an instance of a class that inherited (directly or indirectly) from the specified class ; otherwise False

**5-base_geometry.py:** an empty class `BaseGeometry`

**6-base_geometry.py:** a class BaseGeometry (based on 5-base_geometry.py)

**7-base_geometry.py, tests/7-base_geometry.txt:** a class BaseGeometry (based on 6-base_geometry.py) with method that validates `value`

**8-rectangle.py:** a class Rectangle that inherits from BaseGeometry (7-base_geometry.py) with width and height

**9-rectangle.py:** a class Rectangle that inherits from BaseGeometry (7-base_geometry.py) with width and height and area

**10-square.py:** a class Square that inherits from Rectangle (9-rectangle.py) with size

**11-square.py:** a class Square that inherits from Rectangle (9-rectangle.py) with size and area

