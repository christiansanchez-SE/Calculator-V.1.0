
# Calculator

This is a simple calculator web application built using JavaScript, HTML, and CSS. The calculator performs basic arithmetic operations and has a user-friendly design.

## Features

- **Basic Operations**: Supports addition, subtraction, multiplication, and division.
- **Clear and Delete**: Buttons for clearing the display and deleting individual digits.
- **Responsive UI**: Layout adjusts based on the screen size.
- **Visual Feedback**: Buttons change color when hovered over, enhancing interactivity.

## Tech Stack

- **JavaScript**: Handles the calculator logic and updates the display.
- **HTML**: Provides the structure for the calculator grid and buttons.
- **CSS**: Styles the layout, including a gradient background and button hover effects.

## Demo

![Calculator Screenshot](./calculator-screenshot.png)

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calculator.git
   ```
2. Open the `index.html` file in a web browser to start using the calculator.

## Code Overview

### HTML

The HTML file defines a grid layout for the calculator with rows for numbers, operations, and functions like "AC" (All Clear) and "DEL" (Delete).

### CSS

CSS styles the calculator, applying a gradient background and positioning elements in a grid layout. Each button has hover effects to improve the user experience.

### JavaScript

The JavaScript file contains a `Calculator` class to handle the core functionality:
- **appendNumber**: Adds a number to the display.
- **chooseOperation**: Selects an operation (e.g., addition).
- **compute**: Calculates the result based on the selected operation.
- **updateDisplay**: Refreshes the calculator display to show the current input or result.

## How to Use

1. Click numbers to input them.
2. Select an operation (+, -, *, ÷).
3. Click "=" to see the result.
4. Use "AC" to reset the calculator or "DEL" to delete the last digit.

---
