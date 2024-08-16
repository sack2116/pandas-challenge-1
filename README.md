# Pandas Challenge Project
Module 4 Challenge 3 - DataFrame Transformation

## Overview

This project focuses on transforming a DataFrame using the Pandas library. The main tasks include renaming columns to make them more presentable and handling monetary columns with specific formatting requirements.

### Args

- **For Column Renaming:**
  - `presentable_columns (dict)`: A dictionary mapping original column names to their new, more descriptive names.
  - `money_columns (dict)`: A dictionary mapping original monetary column names to their formatted names.

### Returns

- **Updated DataFrame:**
  - A DataFrame with renamed columns as specified by `presentable_columns` and `money_columns`.

### Examples

- **General Renaming:**
  ```python
  >>> df.rename(columns=presentable_columns, inplace=True)

## PseudoCode
Column Renaming Setup
Import necessary libraries and modules.
Define the presentable_columns and money_columns dictionaries.
Load the DataFrame.
Apply general renaming using presentable_columns.
Apply monetary format renaming using money_columns.
Display the updated DataFrame to verify changes.
Main Program Execution
Load the DataFrame.
Apply column renaming transformations.
Print the updated DataFrame.

## Features
Column Renaming:
Renames columns to reflect more descriptive names for better readability.
Monetary Column Formatting:
Updates column names related to monetary values to reflect their unit in millions.
DataFrame Update:
Applies renaming transformations directly to the DataFrame.
Formatted Output:
Displays the updated DataFrame to verify the applied changes.

## Requirements
Python 3.6 or later
Pandas library


## Setup
Clone this repository to your local machine:
sh
Copy code
git clone https://github.com/sack2116/pandas-challenge-1.git
Navigate to the project directory:
sh
Copy code
cd pandas-challenge-1
Install the required libraries:
sh
Copy code
pip install pandas


## Usage
To run the DataFrame transformation, execute the following script:
sh
Copy code
- python transform_dataframe.py
- Make sure your DataFrame is properly loaded in the script.
- Run the transform_dataframe.py file to apply the column renaming transformations.
- Verify the updated DataFrame to ensure all transformations have been applied correctly.

## Code Structure
transform_dataframe.py: Contains the main script for renaming columns and applying transformations.
data_preprocessing.py: Optional module for additional data preprocessing steps (if applicable).

## How it Works
1. Starting the Program:

* The program begins by importing necessary libraries and loading the DataFrame.

2. Column Renaming Functions:

* presentable_columns renames columns to user-friendly names.
* money_columns updates column names related to monetary values.


3. DataFrame Update:

* The transformations are applied directly to the DataFrame using Pandas' rename method.
* The updated DataFrame is displayed for verification.


4. Results:

* The program completes execution after applying all specified column renaming and formatting transformations.
* The final DataFrame with updated column names is displayed.