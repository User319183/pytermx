# PyTermX

PyTermX is a custom Python console with advanced features.

## Installation

You can install PyTermX using pip:
pip install pytermx

This will start the PyTermX console, where you can enter Python code and see the output.

## Features

PyTermX includes the following features:

- **Syntax highlighting**
- **Autocomplete**
- **Command history**
- **Multi-line input**
- **Customizable prompt**
- And more!

## Usage

To use the `ConsoleX` class in your Python code, you can import it from the `console.py` file:

```python
from console import ConsoleX

# Create a new ConsoleX object
console = ConsoleX()

# Print text in different colors
console.print("This text is red", fg="red")
console.print("This text is green", fg="green")
console.print("This text is yellow", fg="yellow")
console.print("This text is blue", fg="blue")
console.print("This text is magenta", fg="magenta")
console.print("This text is cyan", fg="cyan")
console.print("This text is white", fg="white")

# Print text with different backgrounds
console.print("This text has a black background", bg="black")
console.print("This text has a red background", bg="red")
console.print("This text has a green background", bg="green")
console.print("This text has a yellow background", bg="yellow")
console.print("This text has a blue background", bg="blue")
console.print("This text has a magenta background", bg="magenta")
console.print("This text has a cyan background", bg="cyan")
console.print("This text has a white background", bg="white")

# Print text with different styles
console.print("This text is dim", style="dim")
console.print("This text is normal", style="normal")
console.print("This text is bright", style="bright")
```

This will allow you to print colored text to the console in Python. You can also use other methods of the `ConsoleX` class to clear the console, set the console title, get user input, and more.


## License

PyTermX is licensed under the **MIT License**. See the `LICENSE` file for more information.
