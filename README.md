OIBSIP_BMICalculator_02

Description:
A Python-based BMI Calculator with GUI that allows multiple users to track their BMI history. It calculates BMI, categorizes it, saves the records in a SQLite database, and displays trends using graphs.

--------------------------------------------------------------
TABLE OF CONTENTS

- Installation
- How to Use
- Features
- Description of Commands
- Tech Used
- Contributions
- Methodology

--------------------------------------------------------------
INSTALLATION

1. Download this repository as a ZIP file or clone it.
2. Extract the folder.
3. Open the folder and locate `bmi_calculator.py`
4. Run the script using Python:

   python bmi_calculator.py

Required libraries:

   pip install tkinter matplotlib sqlite3

Note: Tkinter is usually included with Python. Make sure Matplotlib is installed.

--------------------------------------------------------------
HOW TO USE

1. Run the script: python bmi_calculator.py
2. Select an existing user from the dropdown or add a new user.
3. Enter your weight (kg) and height (cm).
4. Click "Calculate BMI" to see your BMI value and category.
5. View your history or trends using the respective buttons.

--------------------------------------------------------------
FEATURES

- Multiple users support with unique names
- BMI calculation and category display
- Save BMI records in SQLite database
- View BMI history per user
- Plot BMI trends over time
- Error handling for invalid input

--------------------------------------------------------------
DESCRIPTION OF BUTTONS

Button                           |         Function
---------------------------------|------------------------------------------
Select or Add User               | Choose an existing user or type new name
Add User                         | Add a new user to the database
Weight (kg) / Height (cm)        | Input fields for BMI calculation
Calculate BMI                    | Calculate BMI and show category
View History                     | Shows the user's BMI history
View Trends                      | Plots BMI trend graph over time

--------------------------------------------------------------
TECH USED

- Language: Python
- Libraries: Tkinter, Matplotlib, SQLite3, Datetime

--------------------------------------------------------------
METHODOLOGY

Workflow of BMI Calculator:

1. Initialization: Setup SQLite database for users and BMI records.
2. User Selection: Select existing user or add a new one.
3. Input: User enters weight (kg) and height (cm).
4. Calculation: BMI calculated using formula: BMI = weight / (height in meters)^2.
5. Categorization: BMI categorized as Underweight, Normal, Overweight, or Obese.
6. Storage: BMI record saved in SQLite with timestamp.
7. History & Trends: Display past records and plot BMI trend graphs.
8. Error Handling: Invalid inputs and duplicate users handled gracefully.

--------------------------------------------------------------

Author: @Ruchitha

THANK YOU!
