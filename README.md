# Sudoku
# Sudoku Validator
This is a simple yet visually appealing web application to validate a 9x9 Sudoku board. It checks both standard Sudoku rules and custom zones for validity.

**Features**
1.Standard Validation: Ensures rows, columns, and 3x3 sub-grids contain unique numbers from 1–9.

2.Custom Zone Validation: Checks unique constraints for specified custom zones (e.g., diagonal 3x3 blocks).

3.Interactive UI: A user-friendly interface with enhanced visuals and responsive design.

**How to Use**
Enter Sudoku Input:

Provide the 9x9 Sudoku board in the textarea.

Use new lines to separate rows, and spaces to separate numbers within a row.

Use 0 to represent empty cells.

**Example input:**

Copy
Edit
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
Validate:

Click the Validate button.

The application will display whether the board is valid or invalid.

**Technologies Used**
HTML: Structure of the web page.

CSS: Stylish, responsive design with a focus on user experience.

JavaScript: Logic for Sudoku validation and user interaction.

Validation Logic
Input Verification:

Checks if the input is a 9x9 grid.

Ensures each cell contains integers between 0–9.

**Standard Sudoku Rules:**

Each row and column must contain unique numbers (ignoring zeros).

Each 3x3 sub-grid must contain unique numbers (ignoring zeros).

**Custom Zone Rules:**

Custom zones (diagonal 3x3 blocks in this case) must also follow the uniqueness constraint.
