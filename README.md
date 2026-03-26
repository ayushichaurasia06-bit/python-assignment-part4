# Python Assignment — Part 4  
## Student Performance Analysis & Prediction

This project analyzes student performance data, creates visualizations, and builds a machine learning model to predict whether a student will pass or fail.


## Overview

The program uses pandas for data analysis, matplotlib and seaborn for visualization, and scikit-learn for machine learning. It demonstrates a complete workflow from data exploration to prediction.


## Dataset

- students.csv  
Contains subject scores, attendance percentage, study hours, and pass/fail status.


## Tasks Implemented

### Task 1 — Data Exploration
- Loaded dataset using pandas  
- Displayed first 5 rows  
- Checked shape and data types  
- Generated summary statistics  
- Counted pass/fail students  
- Calculated subject-wise averages  
- Identified top-performing student  


### Task 2 — Matplotlib Visualizations
Generated and saved:

- plot1_bar.png → Average score per subject  
- plot2_hist.png → Math score distribution  
- plot3_scatter.png → Study hours vs average score  
- plot4_box.png → Attendance (Pass vs Fail)  
- plot5_line.png → Math & Science scores  


### Task 3 — Seaborn Visualizations
Generated and saved:

- plot6_seaborn_bar.png → Subject comparison (Pass vs Fail)  
- plot7_seaborn_scatter.png → Attendance vs performance  


### Task 4 — Machine Learning
- Built Logistic Regression model  
- Split data into train/test  
- Scaled features using StandardScaler  
- Evaluated model accuracy  
- Compared predictions with actual values  
- Displayed feature importance  
- Predicted result for a new student  

---

## How to Run

1. Install libraries:
pip install pandas matplotlib seaborn scikit-learn

2. Open:
part4_visualization_ml.ipynb

3. Run all cells


## Files Included

- part4_visualization_ml.ipynb  
- students.csv  
- plot1_bar.png  
- plot2_hist.png  
- plot3_scatter.png  
- plot4_box.png  
- plot5_line.png  
- plot6_seaborn_bar.png  
- plot7_seaborn_scatter.png  
- README.md  


## Notes

- Dataset is small, so accuracy may vary  
- Focus is on understanding workflow  
- All plots are saved as PNG files  
