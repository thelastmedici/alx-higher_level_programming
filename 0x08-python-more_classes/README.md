# ALX Python More Classes

This repository contains solutions to the ALX Higher Level Programming track's Python More Classes tasks. Each task is implemented in Python and organized in separate directories.

## Table of Contents

- [Task 1: Class Rectangle](#task-1-class-rectangle)
- [Task 2: Class Square](#task-2-class-square)
- [Task 3: Public instance method](#task-3-public-instance-method)
- [Task 4: Static method](#task-4-static-method)
- [Task 5: Class method](#task-5-class-method)
- [Task 6: Static method with a different name](#task-6-static-method-with-a-different-name)
- [Task 7: Class method with a different name](#task-7-class-method-with-a-different-name)
- [Task 8: Rectangle instance to dictionary representation](#task-8-rectangle-instance-to-dictionary-representation)
- [Task 9: Dictionary to JSON string](#task-9-dictionary-to-json-string)
- [Task 10: JSON string to file](#task-10-json-string-to-file)
- [Task 11: Load from file](#task-11-load-from-file)
- [Task 12: Create object from a JSON file](#task-12-create-object-from-a-json-file)
- [Task 13: Pascal's Triangle](#task-13-pascals-triangle)

## Task 1: Class Rectangle

Implement a class `Rectangle` that defines a rectangle.

## Task 2: Class Square

Implement a class `Square` that inherits from `Rectangle` and defines a square.

## Task 3: Public instance method

Add a public instance method `def area(self):` to the `Rectangle` class that returns the area of the rectangle.

## Task 4: Static method

Add a static method `def bigger_or_equal(rect_1, rect_2):` to the `Rectangle` class that returns the rectangle with the biggest area.

## Task 5: Class method

Add a class method `def square(cls, size=0):` to the `Rectangle` class that returns a new instance of `Rectangle` with `width == height == size`.

## Task 6: Static method with a different name

Add a static method `def from_json_string(json_string):` to the `Rectangle` class that returns a list of instances from a JSON string.

## Task 7: Class method with a different name

Add a class method `def save_to_file_csv(cls, list_objs):` to the `Rectangle` class that saves a list of instances to a CSV file.

## Task 8: Rectangle instance to dictionary representation

Add a public instance method `def to_dictionary(self):` to the `Rectangle` class that returns the dictionary representation of a rectangle.

## Task 9: Dictionary to JSON string

Add a static method `def to_json_string(list_dictionaries):` to the `Base` class that returns the JSON string representation of a list of dictionaries.

## Task 10: JSON string to file

Add a class method `def save_to_file(cls, list_objs):` to the `Base` class that writes the JSON string representation of a list of objects to a file.

## Task 11: Load from file

Add a class method `def load_from_file(cls):` to the `Base` class that returns a list of instances.

## Task 12: Create object from a JSON file

Add a class method `def create(cls, **dictionary):` to the `Base` class that returns an instance with all attributes already set.

## Task 13: Pascal's Triangle

Create a function `def pascal_triangle(n):` that returns a list of lists of integers representing Pascal's triangle of `n`.

## Author

- [Christian Joshua](https://github.com/thelastmedici)
