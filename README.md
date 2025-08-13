# Student Performance Analysis

This project analyzes the Student Performance Dataset (`student-mat.csv`) to explore relationships between study time, gender, and final grades (G3).  
The analysis involves data cleaning, statistical summaries, and visualizations to better understand the factors affecting student performance.

## Dataset
- File: student-mat.csv
- Description: The dataset contains student grades and related demographic, social, and school-related features.

## Steps Performed
- Data Loading: Imported the dataset into a Pandas DataFrame.
- Data Inspection: Checked missing values, data types, and dataset shape.
- Data Cleaning:
  - Filled missing numeric values with median.
  - Filled missing categorical values with mode.
  - Removed duplicate rows.
- Exploratory Data Analysis (EDA):
  - Calculated average final grade (G3).
  - Counted students with G3 > 15.
  - Found correlation between study time and G3.
  - Compared average G3 by gender.
- Visualization:
  - Histogram of final grades.
  - Scatter plot of study time vs. final grade.
  - Bar plot of average final grade by gender.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Install dependencies using:
pip install pandas numpy matplotlib seaborn

## How to Run
1. Place the student-mat.csv file in your working directory.
2. Open the Jupyter Notebook or Google Colab file.
3. Run all cells to perform analysis and generate visualizations.

## Notes
- Missing values are handled automatically in the preprocessing stage.
- Analysis is based on numeric and categorical transformations for ease of processing.
- Results may vary if the dataset is updated or modified.

## License
This project is for educational purposes only.  
Dataset credits: UCI Machine Learning Repository – Student Performance Data Set.

by Author - Likhitha Gopal
