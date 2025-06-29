The BMI Calculator Python program is a simple yet effective tool that calculates a user's Body Mass Index (BMI) based on their weight and height. It categorizes the BMI into standard health classifications such as Underweight, Normal, Overweight, and Obese, helping users understand their physical health status. The program uses modular functions to separate the logic for BMI calculation and classification, making the code easy to read and maintain. By prompting the user for their weight, height, and age, the program personalizes the output while maintaining accuracy and clarity. Overall, this code serves as a practical example of user input handling, conditional logic, and basic mathematical computation in Python.

A BMI calculator built using the tkinter GUI library.
Displays BMI based on user inputs for weight (kg) and height (cm).

🧱 Modules Used
tkinter and ttk: For GUI and themed widgets.

math.pow(): To calculate square of height in meters.

🔢 Input Fields
Weight slider: Ranges from 30kg to 200kg.

Height slider: Ranges from 100cm to 250cm.

Sliders are bound to DoubleVar() to store float values.

🧮 BMI Calculation
Triggered by slider movement or button click.

Converts height from cm to meters.
Result is formatted to two decimal places and displayed.

💬 Health Tip Section
Displays a default message advising users to consult a doctor.

Result and tip are shown in a blue-framed area.

⚙️ Features
Real-time BMI updates as sliders move.

“Get Health Tips” button manually updates BMI.

Exception handling for invalid or missing inputs.

🎨 User Interface
Organized with pack() and grid() layout managers.

Uses padding, font styles, and colors for better appearance.

Includes labels to show current weight/height selections.


