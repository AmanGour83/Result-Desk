# 📊 Result Desk-Student Marksheet

Welcome to the **Result Desk**, a Python-based CLI project. This tool loads a marksheet from a CSV file and offers multiple ways to view and analyze student results through data visualization.

## 📁 Project Overview

This program provides:
- Individual student result lookup
- Full class results display
- Subject-wise performance analysis
- Graphical visualizations: Bar, Line, Pie, and Histogram charts

## 📦 Requirements

Make sure you have the following Python packages installed:

```bash
pip install pandas numpy matplotlib
```

## 📂 File Structure

```
marksheet.csv                # Input data file containing student names and their subject marks
main.py                      # Python script (contains the program logic)
README.md                    # Project documentation
```

## 📝 CSV File Format

Your `marksheet.csv` file should follow this structure:

| NAME        | ENGLISH | MATHS | PHYSICS | CHEMISTRY | CS | PE |
|-------------|---------|-------|---------|------------|----|----|
| John Smith  | 35      | 37    | 40      | 32         | 22 | 23 |
| Jane Doe    | 38      | 36    | 39      | 40         | 24 | 25 |
| ...         | ...     | ...   | ...     | ...        | ...| ...|

> `NAME` must be set as the index column in the CSV.

## 🖥️ Features

### 1️⃣ Individual Student Result
- Enter roll number
- View marks in all subjects
- Visualize data using:
  - 📈 Line Graph
  - 📊 Bar Graph
  - 🥧 Pie Chart (marks or marks composition)

### 2️⃣ Class Results Overview
- Displays complete marksheet of all students

### 3️⃣ Subject-wise Analysis
- Select a subject to view histogram
- Histogram shows distribution of marks among all students

### 4️⃣ Exit
- Gracefully quits the program

## 🧠 How It Works

- Reads marksheet from CSV using `pandas`
- Uses `matplotlib` to plot graphs
- Loops through the menu using a `while` loop
- Allows repeated graph viewing for better exploration

## 📌 Notes

- Designed to run in a terminal or console-based Python environment
- Assumes student roll numbers align with their row position in the CSV (i.e., 1-based indexing)



> Made with ❤️ by Aman 
