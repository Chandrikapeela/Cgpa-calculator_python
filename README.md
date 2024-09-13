# CGPA Calculator

## Overview

The GPA Calculator is a Python application designed to calculate the Grade Point Average (GPA) for a semester based on user input for various courses. Users can choose to enter either the total marks for each course or the individual marks for Mid Sem, Internals, and End Sem. The application calculates the GPA using the inputted data and displays the result.

## Features

- **Flexible Input Options**: Enter either total marks for each course or detailed marks for Mid Sem, Internals, and End Sem.
- **Automatic GPA Calculation**: Computes the GPA based on user input.
- **Error Handling**: Validates entered marks to ensure they are within a valid range and provides error messages when necessary.

## Installation

This application requires Python. You can run the script using any Python 3.x interpreter.

1. **Download or Clone the Repository**

   You can download the source code as a ZIP file or clone the repository using Git:
   ```bash
   git clone https://github.com/Chandrikapeela/Cgpa-calculator_python.git
   ```

2. **Navigate to the Project Directory**

   Change to the project directory:
   ```bash
   cd gpa-calculator
   ```

3. **Run the Script**

   Execute the script using Python:
   ```bash
   python gpa_calculator.py
   ```

## Usage

1. **Start the Application**:
   - Run the script in your terminal or command prompt.

2. **Input Details**:
   - Enter the number of courses.
   - Choose how you want to input marks:
     - Enter `0` to input total marks for each course.
     - Enter `1` to input Mid Sem, Internals, and End Sem marks separately.

3. **Enter Course Information**:
   - For each course, provide the course name and total credits.
   - Input the required marks based on your choice.

4. **View Results**:
   - The GPA for the semester will be calculated and displayed.

## Example

Here’s a brief example of the interaction with the application:

```
------------------------------------------
GPA Calculator: 
------------------------------------------
Enter Number Of Courses: 3
Enter 1 to individually enter Mid Sem, Internals & End Sem Marks
Else Enter 0 to enter Total Marks: 1
Enter Course Name: Math
Enter Total Credits Of Math: 3
Enter Your Mid Sem Marks for Math: 85
Enter Your Internal Marks for Math: 80
Enter Your End Sem Marks for Math: 90

Enter Course Name: Science
Enter Total Credits Of Science: 4
Enter Your Mid Sem Marks for Science: 75
Enter Your Internal Marks for Science: 70
Enter Your End Sem Marks for Science: 80

Enter Course Name: History
Enter Total Credits Of History: 3
Enter Your Mid Sem Marks for History: 90
Enter Your Internal Marks for History: 85
Enter Your End Sem Marks for History: 95

Your Credits for this Semester is: 8.67
```

## Code Explanation

- **Function: `calculate_gpa(num_courses, marks)`**
  - **Parameters**:
    - `num_courses`: Number of courses to calculate GPA for.
    - `marks`: Determines the type of marks input (0 for total marks, 1 for detailed marks).
  - **Returns**: The calculated GPA for the semester as a float.
  - **Logic**:
    - Collects course information and marks from the user.
    - Validates and processes the marks.
    - Computes GPA based on the provided course credits and marks.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact peelachandrika@gmail.com

---
