# PyTermX

PyTermX is a Python library for enhancing console interactions. It provides a variety of features such as colored text, styled text, console window manipulation, and more.

## Features

- Colored and styled text output
- Console window manipulation (clear, resize, move, hide/show)
- User input and confirmation
- Progress bar display
- Alert messages
- Logging with different levels

## Installation

As this project is not on PyPI, you can install it by cloning the repository and installing it manually.

```bash
git clone https://github.com/User319183/pytermx.git
cd pytermx
python setup.py install
```

```python
from console import ConsoleX

console = ConsoleX()

# print colored text
console.print("Hello, World!", fg="green")

# display a progress bar
console.progress("Loading", length=50, delay=0.1)

# log a message
console.log("This is a debug message", LogLevel.DEBUG)

# clear the console
console.clear()

# set the console title
console.title("My Console")

# set the console size
console.size(80, 24)

# move the console window
console.move(100, 100)

# hide the console
console.hide()

# show the console
console.show()

# get user input
input = console.input("Enter something: ")

# pause the console
console.pause()

# confirm an action with the user
confirmation = console.confirm("Are you sure? (y/n)")

# display an alert
console.alert("Alert", "This is an alert message", style="warning")
```

This will allow you to print colored text to the console in Python. You can also use other methods of the `ConsoleX` class to clear the console, set the console title, get user input, and more.


## Future Updates

Coming soon with new features & improved preformance.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, please open an issue on the GitHub repository.

