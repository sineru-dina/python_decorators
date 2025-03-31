# My Learnings on decorators in Python

This repository is dedicated to my exploration of Python's class-related features, specifically:

- `@dataclass`
- `@classmethod`
- `@staticmethod`

Each section includes simple examples that showcase the use of these features and demonstrate their utility in real-world programming scenarios. These examples will help solidify the concepts of object-oriented programming in Python.

## @dataclass

The `@dataclass` decorator is a powerful feature in Python that automatically generates special methods like `__init__`, `__repr__`, `__eq__`, and others based on class attributes. This allows for cleaner and more maintainable code when dealing with classes designed to store data.

## @classmethod

The `@classmethod` decorator defines a method that is bound to the class, rather than its instances. It can modify class-level attributes and is often used for alternative constructors or methods that need to operate on the class itself.

## @staticmethod

The `@staticmethod` decorator defines a method that does not require access to class or instance attributes. It's typically used for utility methods that do not depend on the state of the object but belong logically to the class.
