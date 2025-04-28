Data Analysis 2025 - Practical Assignment 1
General Information
Assignment: Data Manipulation and Cleaning (Missing Data & Outliers)
Dataset Name: Hormonal and Biochemical Profile in Patients
Source: Internal company database
Author/Owner: Internal
Creation/Update Date: Not specified
License: Educational use
Purpose: Practical class for missing data handling and outlier detection.
Dataset Structure
Format: CSV
Size: 1148 rows × 41 columns
Main Columns: Hormone levels, lipid profiles, antioxidant levels, diagnosis factors.
R Version and Packages
R Version: 4.5.0
Main Libraries Used: naniar, mice, dbscan, dplyr, ggplot2
Procedures Used
Missing Data Analysis (naniar visualization, MCAR test)
Imputation (PMM method and Random Forest method)
Outlier Detection (LOF algorithm)
Visualizations and conclusions
Files
DataSet_No_Details.csv: Original data before manipulation.
code.R: R script used for data cleaning, imputation, and analysis.
imputed_handle_MD_df_final.csv: Data after imputation and cleaning.
graphs/: Folder containing plots like density and boxplots.
