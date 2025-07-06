# CodeAlpha_Calculator
Frontend Internship Project for CodeAlpha
# Simple Calculator

This is a basic calculator web application built with HTML and CSS. It allows users to perform simple arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Responsive and modern UI
- Supports basic arithmetic operations: `+`, `-`, `*`, `/`
- Clear (`AC`) and delete (`DE`) functions
- Decimal point support
- Double zero (`00`) button

## Project Structure

- [`index.html`](index.html): Main HTML file containing the calculator layout and inline button logic.
- [`style.css`](style.css): CSS file for styling the calculator and making it visually appealing.
- [`.vscode/settings.json`](.vscode/settings.json): VS Code settings for Live Server port configuration.

## How to Use

1. Open the project folder in Visual Studio Code.
2. Open `index.html` in your browser. If you use the Live Server extension, it will run on port 5501.
3. Use the calculator by clicking the buttons to enter numbers and operations.
4. Click `=` to evaluate the expression.
5. Use `AC` to clear the display and `DE` to delete the last character.

## Notes

- The calculator uses the JavaScript `eval()` function for evaluation, which is suitable for simple use cases but not recommended for production or untrusted input.
- All logic is handled inline via the
