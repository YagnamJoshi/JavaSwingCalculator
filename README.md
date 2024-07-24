# Java Swing Calculator

A simple calculator application built using Java Swing for the graphical user interface. This project demonstrates the use of basic components such as buttons and text areas to create a functional calculator.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Percentage calculation
- Negation of numbers
- Clear all input (AC button)
- Decimal point support

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your system

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/JavaSwingCalculator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd JavaSwingCalculator
    ```
3. Compile the Java code:
    ```bash
    javac calc.java
    ```
4. Run the application:
    ```bash
    java calc
    ```

## Usage

Upon running the application, a calculator window will appear with the following functionalities:

- `AC`: Clears all input
- `+/-`: Toggles the sign of the current number
- `%`: Calculates the percentage
- `÷`, `X`, `-`, `+`: Performs division, multiplication, subtraction, and addition respectively
- Number buttons (`0-9`): Inputs the corresponding number
- `. `: Adds a decimal point
- `=`: Computes the result of the entered expression

## Code Overview

The `calc` class implements the `ActionListener` interface to handle button click events. The GUI components are created and added to the frame in the constructor, and the `actionPerformed` method handles the logic for each button click.

### Main Components

- `JFrame`: The main window of the application
- `JTextArea`: Displays the input and results
- `JButton`: Represents each button in the calculator

### Logic

The calculator uses flags to manage states:
- `flag1`: Indicates whether the display should be cleared
- `flag2`: Indicates whether a decimal point has been added
- `flag3`: Indicates whether an operation is in progress

The `calculate` method performs the arithmetic operations based on the operator selected.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## Acknowledgments

- Java Swing documentation for providing guidance on building GUI applications.
