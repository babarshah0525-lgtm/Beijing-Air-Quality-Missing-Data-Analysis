# Beijing-Air-Quality-Missing-Data-Analysis
Overview

This project investigates missing values in Beijing's PM2.5 air-quality dataset.
Rather than simply filling missing readings, the project explores whether missing observations occur randomly or cluster around periods of severe pollution.
The analysis also evaluates how common imputation techniques can alter pollution trends and potentially lead to misleading conclusions.
Research Question
Are missing PM2.5 readings randomly distributed, or do they occur more frequently during high-pollution events?
Dataset

Dataset contains hourly air-quality measurements including:
PM2.5 concentration
Temperature
Pressure
Wind Direction
Dew Point
Timestamp information

Source:

UCI Machine Learning Repository
Project Workflow
1. Data Loading
Imported dataset using Pandas
Inspected dataset structure
Verified column types
2. Missing Value Analysis
Counted missing observations
Visualized missing-value patterns
Generated missing-value matrix
3. Missing Data Investigation
Defined high-pollution thresholds
Examined whether missing readings cluster around pollution spikes

5. Imputation Experiments

Implemented and compared:
Forward Fill
Backward Fill
Mean Imputation
Linear Interpolation

5. Distribution Analysis

Compared original and imputed distributions using histograms.
Technologies Used
Python
Pandas
Matplotlib
Missingno
Jupyter Notebook

Key Findings

Finding 1
PM2.5 contains significant missing observations.
Finding 2
Missing readings are not uniformly distributed over time.
Finding 3
Different imputation methods produce noticeably different PM2.5 distributions.
Finding 4
Simple imputation methods may distort extreme pollution events.

Example Visualizations

Missing Value Matrix
<img width="2080" height="881" alt="Missing Value Matrix" src="https://github.com/user-attachments/assets/1f3f759d-062e-462f-95ea-39b6a4f3e93a" />
Missing Value Distribution
<img width="1324" height="701" alt="image" src="https://github.com/user-attachments/assets/48074cbd-88cf-45ef-86e4-fc347759ed8d" />
Imputation Comparison
<img width="1014" height="547" alt="image" src="https://github.com/user-attachments/assets/5bd70faa-7e6d-4aa4-b4ab-20fad508c5af" />

Future Improvements

Random Forest Imputation
KNN Imputation
Seasonal Decomposition
Time-Series Forecasting
Missingness Classification
