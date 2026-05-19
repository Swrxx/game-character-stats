# Game Character Stats Tracker

A Python project that creates a game character with basic stats such as name, health, mana, and level.  
The project uses Object-Oriented Programming concepts like classes, properties, setters, and the `__str__` method.

## What I learned

- How to create a Python class.
- How to use the `__init__` method to initialize object attributes.
- How to use `@property` to create getters.
- How to use setters to validate and control attribute values.
- How to prevent health and mana from going below or above allowed limits.
- How to use `__str__` to return a formatted string representation of an object.
- How to update object state with methods like `level_up`.

## Main challenge

The hardest part was understanding how getters and setters work together with internal attributes like `_health` and `_mana`.

I also had to pay close attention to exact string formatting, because small details like spaces, quotes, and `\n` line breaks can make the tests fail.

## How to run

Make sure Python is installed on your machine.

Then run:

```bash
python main.py
