Adding X and Y Coordinates to a CSV File
This project is a simple Python script that uses the geopy library to add longitude (X) and latitude (Y) coordinates to a CSV file. The script takes an existing column with place names (like states) and converts them into precise geographical coordinates.

Key Features
Geocoding: Converts place names into geographic coordinates (X, Y).

Easy to Use: Works on any CSV file with a column containing place names.

Error Handling: Gracefully handles locations that can't be found and logs them.

Output: Saves the processed data to a new CSV file.

How to Run
Follow these steps to get the script running with your data:

1. Requirements
Make sure you have Python installed. Then, install the necessary libraries using pip:

Bash

pip install pandas geopy
2. Prepare Your File
Place your CSV file in the same directory as the script.

Make sure your file has a column named State, or modify the column name in the code.

3. Modify the Code
Open the script and adjust the file path and column name variables as needed:

Python

# Path to your input CSV file
file_path = r'D:\MySkills\State.csv'

# Name of the column containing the place names
column_name_to_geocode = 'State'
4. Run the Script
Open your terminal or Git Bash in the project folder and run the script:

Bash

python your_script_name.py
Note: Replace your_script_name.py with the actual name of your Python file.

Output
After the script runs successfully, you'll find a new file named geocoded_final_output.csv in the same directory. This file will contain all your original data plus two new columns: X_Coordinate (for longitude) and Y_Coordinate (for latitude).

Contributing
If you have ideas for improving this script, feel free to open a pull request or report an issue. Contributions are welcome!
