# health-care-data-cleaning
Overview:
This project helps clean healthcare data to improve disease prediction accuracy. The script handles missing values, inconsistent records, and noisy data.

Features:

Handling Missing Data
Fills missing numerical values with the mean.
Fills missing categorical values with the most frequent (mode).
Handling Inconsistent Data
Converts text data to lowercase for consistency.
Removes duplicate records.
Handling Noisy Data
Removes outliers using the Z-score method (values beyond 3 standard deviations from the mean).

How to Use:
Upload a CSV healthcare dataset.
Run the script.
The cleaned data is saved as 'cleaned_healthcare_data.csv'.

Requirements:
Python
Pandas
NumPy
SciPy
