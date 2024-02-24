# ALX 0x0C Python - Almost a Circle

This project is part of the ALX Higher Level Programming curriculum and focuses on object-oriented programming in Python. The goal of this project is to create a base class called `Base` that will be used for the implementation of two other classes: `Rectangle` and `Square`. These classes will represent geometric shapes and will have various attributes and methods.

## Project Structure

The project is organized as follows:

- `models/` directory: Contains the implementation of the `Base`, `Rectangle`, and `Square` classes.
- `tests/` directory: Contains unit tests for the classes implemented in the `models/` directory.
- `main.py`: A sample script that demonstrates the usage of the classes.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/thelastmedici/alx-python-almost-a-circle.git`
2. Navigate to the project directory: `cd alx-python-almost-a-circle`
3. Run the `main.py` script to see a demonstration of the implemented classes: `python main.py`

## Usage

To use the `Rectangle` and `Square` classes in your own projects, follow these steps:

1. Import the classes: `from models.rectangle import Rectangle` and `from models.square import Square`
2. Create instances of the classes: `rectangle = Rectangle(width, height, x, y, id)` and `square = Square(size, x, y, id)`
3. Use the available methods to manipulate the objects. For example, you can use the `area()` method to calculate the area of a shape, or the `display()` method to print a visual representation of the shape.

## Testing

To run the unit tests for the implemented classes, follow these steps:

1. Navigate to the `tests/` directory: `cd tests`
2. Run the test script: `python test_models.py`

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
