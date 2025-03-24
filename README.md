# GridXcel - Excel Like App

GridXcel is a powerful web-based application designed to mimic the functionality of an Excel spreadsheet. Built using HTML, CSS, JavaScript, and Bootstrap, this app allows users to perform complex calculations and work with formulas, just like in Microsoft Excel. It provides a responsive, user-friendly interface and is optimized for mobile devices.

## Key Features:
- **Responsive Design**: Fully responsive layout that works seamlessly across mobile and desktop devices.
- **Interactive Table**: A dynamic grid that can accommodate data entry, selection, and formula calculations.
- **Formula Support**: A wide range of commonly used formulas for complex calculations and data analysis.
- **Real-time Calculation**: Instant formula evaluation as you input values into the cells.
- **Formula Bar**: Easily enter and edit formulas with the integrated formula bar.

## Formulas Supported:

GridXcel includes the following 25 formulas, enabling you to perform a wide range of mathematical and data manipulation tasks:

### 1. SUM
Calculates the sum of a specified range of cells.
Example:  
`=SUM(A1:A5)`

### 2. AVERAGE
Calculates the average of a specified range of cells.
Example:  
`=AVERAGE(A1:A5)`

### 3. MIN
Finds the minimum value in a specified range of cells.
Example:  
`=MIN(A1:A5)`

### 4. MAX
Finds the maximum value in a specified range of cells.
Example:  
`=MAX(A1:A5)`

### 5. COUNT
Counts the number of cells that contain numbers in a specified range.
Example:  
`=COUNT(A1:A5)`

### 6. IF
Performs conditional logic to return a value based on a condition.
Example:  
`=IF(A1>5, "Yes", "No")`

### 7. ROUND
Rounds a number to a specified number of decimal places.
Example:  
`=ROUND(A1, 2)`

### 8. CONCATENATE
Joins two or more strings together into one.
Example:  
`=CONCATENATE(A1, " ", B1)`

### 9. LEN
Returns the length of a string.
Example:  
`=LEN(A1)`

### 10. PRODUCT
Multiplies a range of numbers.
Example:  
`=PRODUCT(A1:A5)`

### 11. SQRT
Calculates the square root of a number.
Example:  
`=SQRT(A1)`

### 12. MOD
Returns the remainder after dividing one number by another.
Example:  
`=MOD(A1, A2)`

### 13. POWER
Raises a number to the power of another number.
Example:  
`=POWER(A1, 2)`

### 14. ABS
Returns the absolute value of a number.
Example:  
`=ABS(A1)`

### 15. MAXA
Returns the largest value in a range of values, including text.
Example:  
`=MAXA(A1:A5)`

### 16. MINA
Returns the smallest value in a range of values, including text.
Example:  
`=MINA(A1:A5)`

### 17. TODAY
Returns the current date.
Example:  
`=TODAY()`

### 18. NOW
Returns the current date and time.
Example:  
`=NOW()`

### 19. TRIM
Removes extra spaces from a text string.
Example:  
`=TRIM(A1)`

### 20. ISNUMBER
Checks whether a value is a number.
Example:  
`=ISNUMBER(A1)`

### 21. ISEVEN
Checks if a number is even.
Example:  
`=ISEVEN(A1)`

### 22. ISODD
Checks if a number is odd.
Example:  
`=ISODD(A1)`

### 23. IFERROR
Returns a value if there is no error, and an alternative value if there is an error.
Example:  
`=IFERROR(A1/B1, "Error")`

### 24. TEXT
Formats a number as text in a specific format.
Example:  
`=TEXT(A1, "0.00")`

### 25. VLOOKUP
Looks up a value in a table and returns a value in the same row from a specified column.
Example:  
`=VLOOKUP(A1, B1:C5, 2, FALSE)`

## How to Use GridXcel

1. **Access the App**: Open the `index.html` file in a browser.
2. **Enter Data**: Click on any cell to input values.
3. **Enter Formulas**: In the formula bar, enter a formula starting with `=`. For example, `=SUM(A1:A5)` will calculate the sum of the values in cells A1 to A5.
4. **Cell References**: Use cell references (e.g., A1, B2) in your formulas, just like in Excel.
5. **Formula Results**: The result of the formula will be displayed in the cell where the formula was entered.

## Installation

GridXcel can be run directly in your web browser. Follow these simple steps:

1. **Clone or Download**: Download or clone the repository containing `index.html`.
2. **Open the HTML File**: Open the `index.html` file in your browser to start using the app.
3. **Edit and Save**: Make changes to the grid and formulas as needed. The data will not be saved automatically unless you integrate a back-end system.

## Customization

- **Modify Rows and Columns**: The number of rows and columns can be modified in the JavaScript section of the code to better suit your needs.
- **Extend Formulas**: New formulas can be added by adding new parsing functions to the `parseFormula` function.

## License

This project is open-source and is available under the MIT License. Feel free to use, modify, and distribute it as you wish.
