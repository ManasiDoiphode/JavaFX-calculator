# JavaFX Calculator

## Overview
This is a basic desktop calculator built using JavaFX. It supports standard arithmetic operations like addition, subtraction, multiplication, and division, all handled through a user-friendly graphical interface.

## Features
- Simple, intuitive UI designed with JavaFX
- Supports basic arithmetic operations: `+`, `-`, `*`, `/`
- Responsive layout with GridPane
- Handles multiple operations and user inputs
- Error handling for division by zero

## How It Works
### User Interface
- A non-editable display field at the top shows the input and results.
- Buttons arranged in a grid layout:
  - Digits (0-9)
  - Decimal point
  - Operators: `+`, `-`, `*`, `/`
  - Special functions: `C` (clear), `=` (equals)

### Functionality
- **Display Updates**: Input is displayed as users click buttons.
- **Operator Selection**: Stores the first operand and selected operator.
- **Calculation**: When `=` is pressed, computes and displays the result.
- **Clear**: Resets the calculator to its default state.

## Usage
### Running the Program
1. Ensure JavaFX is properly set up in your development environment.
2. Compile and run the application using:
   ```bash
   javac Calculator.java
   java Calculator
   ```

### Using the Calculator
- Launch the app and enter numbers using the on-screen buttons.
- Click an operator (`+`, `-`, `*`, `/`), then enter the second number.
- Press `=` to view the result.
- Use `C` to reset the calculator at any time.

## Example
1. Input: `7`, `+`, `3`, `=`  
   Output: `10`

2. Input: `9`, `/`, `0`, `=`  
   Output: `0` (Handled internally to avoid division by zero errors)

## Limitations
- Does not support parentheses or complex expressions.
- No keyboard support (only on-screen buttons).
- Limited to one operation at a time.

## Future Improvements
- Add support for keyboard input.
- Enable operation chaining (e.g., 3 + 4 * 2).
- Implement scientific functions (sin, cos, log, etc.).
- Use more advanced layout managers for responsiveness.

## License
This project is open-source and free to use under the MIT License.

