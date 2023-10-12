# Calulator-Application-
Calculaor Application Using Visual Studio 2022 and C++
# Simple Calculator Application

This is a simple calculator application developed in C++ using Visual Studio Code. The application provides a graphical user interface for performing basic arithmetic operations, such as addition, subtraction, multiplication, and division.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Screenshots](#screenshots)
- [How to Use](#how-to-use)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Description

This calculator application is a basic tool for performing arithmetic calculations conveniently through a user-friendly graphical interface. It offers the following features:

## Features

- Addition: Perform addition operations by entering numbers and clicking the "+" button.
- Subtraction: Subtract one number from another using the "-" button.
- Multiplication: Multiply numbers using the "*" button.
- Division: Divide one number by another using the "/" button.
- Error Handling: The application gracefully handles invalid inputs and displays an "Error" message when necessary.

## Screenshots

*Insert screenshots of your application here.*

![Screenshot 1](/screenshots/screenshot1.png)

![Screenshot 2](/screenshots/screenshot2.png)

You can add screenshots of your application to illustrate its user interface and functionality.

## How to Use

To use the calculator application, follow these steps:

1. Download or clone the repository to your local machine.

2. Open the project in Visual Studio Code.

3. Build and run the application.

4. Use the graphical user interface to input numbers and perform calculations. You can click on digit buttons, operation buttons, and the equal sign to perform calculations.

5. The result will be displayed in the result box, and you can check the history of calculations in the "History" tab.

Enjoy using the simple calculator application!

## Installation

Provide instructions for building and running your application. You can mention any dependencies or system requirements.

## Contributing

If you'd like to contribute to this project, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


# Simple Calculator Application

This is a simple calculator application developed in C++/CLI using Visual Studio Code. The application provides a graphical user interface for performing basic arithmetic operations, such as addition, subtraction, multiplication, and division.

## Table of Contents
- [Key Components](#key-components)
- [How to Use](#how-to-use)

## Key Components

1. **Including Necessary Libraries**:
   The code starts by including the required libraries and namespaces. It utilizes the Windows Forms library to create a graphical user interface for the calculator.

2. **CalculatorForm Class**:
   This class defines the main form for the calculator application. It inherits from the `Form` class provided by the Windows Forms library.

3. **Private Member Variables**:
   Inside the `CalculatorForm` class, several private member variables are declared. These include:
   - `inputBox`: A TextBox control for user input.
   - `resultLabel`: A Label (although not used in the code).
   - `resultList`: A ListBox to display a history of calculations.
   - `calculateButton`: A Button for performing calculations.
   - `clearButton`: A Button for clearing the input.
   - `resultBox`: Another TextBox for displaying the calculation result.
   - Various `Color` objects for defining colors used in the UI.
   - `TabControl` named `tabs` for managing multiple tabs within the form.

4. **CalculatorForm Constructor**:
   The constructor initializes the calculator's graphical user interface. It sets the form's properties such as title, size, and background color.

5. **Input Tab**:
   The constructor creates the Input tab, where users can input numbers and operations. It adds buttons for digits 0-9, basic arithmetic operations, and an equal sign for calculation.

6. **NumberButton_Click Function**:
   This function is an event handler for digit buttons. When a digit button is clicked, the corresponding digit is appended to the input text.

7. **OperationButton_Click Function**:
   This function is an event handler for operation buttons. When an operation button is clicked, the corresponding operation symbol is appended to the input text.

8. **ClearButton_Click Function**:
   This function is an event handler for the "C" button, which clears the input text and the result box.

9. **CalculateResult Function**:
   This function is called when the equal sign ("=") button is pressed or when the Enter key is pressed. It evaluates the input expression, displays the result in the result box, and adds the calculation to the history list.

10. **InputBox_KeyPress Function**:
    This function handles the Enter key press event and invokes the calculation function. It prevents the Enter key from being displayed in the input box.

11. **Calculate Function**:
    The `Calculate` function takes the input expression, evaluates it, and updates the result box and history list. If there is an error in the expression, it displays "Error."

12. **Main Function**:
    The `main` function is the entry point of the program. It initializes the Windows Forms application, creates an instance of the `CalculatorForm` class, and runs the application.

## How to Use

To use the calculator application, follow these steps:

1. Download or clone the repository to your local machine.

2. Open the project in Visual Studio Code.

3. Build and run the application.

4. Use the graphical user interface to input numbers and perform calculations. You can click on digit buttons, operation buttons, and the equal sign to perform calculations.

5. The result will be displayed in the result box, and the history of calculations will be shown in the "History" tab.

Enjoy using the simple calculator application!

