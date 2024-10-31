
# Base Addition Program

This Python program adds two numbers provided in a specified base (e.g., binary, octal, decimal, hexadecimal) and outputs the result in the same base.

## Features

- Add numbers in various bases (2, 8, 10, 16, etc.).
- Handles input and output efficiently.
- Validates base and number formats.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Run the Program:**
   ```bash
   python base_addition.py
   ```

3. **Input Instructions:**
   - Enter the first number when prompted.
   - Enter the second number when prompted.
   - Enter the base (e.g., 2 for binary, 8 for octal, 10 for decimal, 16 for hexadecimal).

4. **Output:**
   The program will display the sum of the two numbers in the specified base.

## Example

### Input:
```
Enter 1st number: 1010
Enter 2nd number: 1101
Enter base: 2
```

### Output:
```
The sum of 1010 and 1101 in base 2 is: 10111
```

## Valid Inputs

- **Base 2 (Binary):** `0`, `1`
- **Base 8 (Octal):** `0` to `7`
- **Base 10 (Decimal):** `0` to `9`
- **Base 16 (Hexadecimal):** `0` to `9`, `A` to `F`

## Limitations

- Ensure the numbers are valid for the specified base.
- The program does not currently handle invalid inputs gracefully.
