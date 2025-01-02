# Package Sorting System

This Python script is designed to sort packages based on their dimensions and mass into three categories: `REJECTED`, `SPECIAL`, or `STANDARD`. The categories are determined by specific rules on package size and mass. The program prompts the user to input the width, height, length, and mass of the package, and then decides how it should be dispatched.

## Rules for Sorting:

1. **REJECTED**: 
    - A package is considered "bulky" if:
        - The product of width, height, and length is greater than or equal to 1,000,000 cm³.
        - OR any dimension (width, height, or length) is greater than or equal to 150 cm.
    - A package is considered "heavy" if its mass is greater than or equal to 20 kg.
    - If the package is both bulky and heavy, it is classified as **REJECTED**.

2. **SPECIAL**:
    - A package is classified as "SPECIAL" if it is either bulky **OR** heavy, but not both.
   
3. **STANDARD**:
    - A package is classified as **STANDARD** if it does not meet the criteria for "bulky" or "heavy".

## Features:

- Input package dimensions and mass.
- The program automatically determines whether the package is bulky, heavy, or both.
- It assigns the package to one of the following categories: **REJECTED**, **SPECIAL**, or **STANDARD**.

## Installation and Usage:

### Requirements:
- Python 3.x installed on your system.

### Steps to run the program:
1. Clone or download the repository to your local machine.
2. Open a terminal (or command prompt) and navigate to the folder containing the script.
3. Run the Python script by typing:
   ```bash
   python package_sorting.py
4. Enter the package dimensions (width, height, length) and mass when prompted.
5. The program will display the appropriate category for the package.

## Error Handling:
If the user enters non-numeric input for the dimensions or mass, the program will notify them and ask for valid numeric values.

## License
Feel free to use and modify the code.

## Author
Mohan Karthik Vijayakumar

