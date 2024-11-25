![Math & Conversation Module](https://github.com/CalestialAshley35/Math-Module/raw/a6fa469a7aa1f4f7356da953564e8c6e63551356/file-Kgvvzu3IapvZpJ1QNV8s2LXq.jpg)
# Math & Conversion Module

This is a simple Math and Conversion module that allows users to perform various mathematical operations and unit conversions directly from the input field. Users can enter commands such as arithmetic expressions, square roots, and unit conversions, and get the result instantly.

## Features:
- **Basic Math Operations**: Addition, subtraction, multiplication, division
- **Square Root**: Evaluate the square root of a number
- **Unit Conversion**: Convert pounds to kilograms and vice versa
- **Chemical Formula**: Solve chemical formulas (e.g., `$chemical=H2O`)
- **Trigonometric and Logarithmic Functions**: Solve for Sin, Cos, Logarithms
- **Advanced Math Operations**: Supports operations like `$maths:+`, `$maths:put -`

# Commands:

### Basic Math Operations:
`x + y, x - y, x * y, x / y`

### Square Root:

`√25  (example for calculating square root)`

### Unit Conversion:
- Convert pounds to kilograms:
`$conversation pounds=10 in kg`

- Convert kilograms to pounds:
`$conversation kg=10 in pounds`

### Trigonometric and Logarithmic Functions:
- Solve Sin, Cos, and Logarithms:
- `$advanced q=sin(30)`  (example for Sin)
- `$advanced q=cos(45)`  (example for Cos)
- `$advanced q=log(100)` (example for Log)

### Chemical Formula:
- Solve a chemical formula:

`$chemical=H2O  (example for a chemical formula)`

### Advanced Math Operations (`$maths`):
- Add numbers:

`$maths:+ x y`

- Subtract numbers:

`$maths:put - x y`

- Example:

`$maths:+ 5 3` → Result: 8 `$maths:put - 5 3` → Result: -8

# MathDB
MathDB is an Powerful Libary for Storing Maths and Also Download it as JSON 
Click the "Try MathDB" button, then type the command `#mathdb connect` to get started. After that, you can enter custom math expressions, such as `#savedb math=1+1 ans=2`.  Type the `#downloaddb #maths` to Download it as JSON
MathDB supports various operations, including square roots, sin, cos, log, tan, and more. Each calculation will be saved automatically. To view all saved math operations, simply type `#maths`.

## Usage:

To use this module in your project, simply include the following CDN URL in your HTML file:

```<script src="https://cdn.jsdelivr.net/gh/CalestialAshley35/Math-Module@main/module.js"></script>```

then, you can use the module by calling the `startModule()` function with a button click or another event. 
