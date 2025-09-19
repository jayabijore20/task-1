Temperature & Calculator Utilities

Author: Jaya Bijore – Aspiring Data Analyst

This repository contains a set of Python programs developed while practicing core Python skills, file handling, and data analysis with pandas.

📂 Project Structure
.
├─ temperature_converter.py      # Interactive Celsius ↔ Fahrenheit converter
├─ simple_calculator.py          # CLI calculator supporting add, subtract, multiply, divide
├─ temp_data_creator.py          # Generates a CSV file of daily temperatures
├─ avg_temperature_summary.py    # Reads temp.csv and outputs average temperature summary
├─ avg_temperature_interactive.py# Interactive version that asks user for file & fill method
├─ temp.csv                      # Sample temperature dataset (generated)
└─ README.md                     # Project documentation (this file)

📝 Overview

The project demonstrates:

Python fundamentals – functions, conditionals, loops, error handling.

Interactive CLI programs – reading user input and printing results.

pandas for data analysis – reading/writing CSV files, handling missing values, calculating averages.

⚙️ Components
1. Temperature Converter

Command-line tool to convert Celsius ↔ Fahrenheit.

Accepts inputs like 23C, 75F, or numeric value plus unit prompt.

Handles invalid input gracefully.

2. Simple Calculator

Four operations: Add, Subtract, Multiply, Divide.

Uses a dictionary to map menu choices to functions.

Includes division-by-zero protection.

3. Temperature Data & Average Summary

temp_data_creator.py builds a sample temp.csv with daily temperatures and a few missing values.

avg_temperature_summary.py:

Reads temp.csv

Lets you choose how to fill missing temperatures (drop, mean, or zero)

Calculates average temperature in °C and °F

Saves a one-row summary to avg_temp_result.csv

avg_temperature_interactive.py offers the same logic but prompts the user for file names and method at runtime.

🚀 How to Run

Clone the repository

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


Install dependencies

pip install pandas


Run individual scripts

Temperature Converter

python temperature_converter.py


Simple Calculator

python simple_calculator.py


Average Temperature Summary (auto)

python avg_temperature_summary.py


Average Temperature Summary (interactive)

python avg_temperature_interactive.py

🏁 Key Features & Learnings

Clean handling of user input and exceptions.

Demonstrates both automated and interactive data processing with pandas.

Shows how to generate and reuse CSV datasets for analysis.

🏷 License

This project is provided under the MIT License—feel free to use and adapt it for learning or other projects.
