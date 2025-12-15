# Task 1  Data Cleaning & Preprocessing  

## Objective
- Load the dataset using pandas  
- Identify and handle missing values  
- Remove duplicate rows  
- Handle outliers in selected columns (CRIM, ZN, B, LSTAT, MEDV)  
- Standardize the dataset using StandardScaler  
- Save the cleaned dataset  

## Steps
1. Loaded the raw dataset (space‑separated, no header) and added column names.  
2. Checked dataset info, summary statistics, missing values, and duplicates.  
   - No missing values  
   - No duplicate rows  
3. Detected and removed outliers using the IQR method for CRIM, ZN, B, LSTAT, MEDV.  
   - Rows reduced from 506 → 297  
4. Applied StandardScaler to normalize all features.  
5. Saved the cleaned dataset as `cleaned_preprocessed_dataset.csv`.  

## Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit‑learn  
- Matplotlib / Seaborn  

## Files
- `Task1_Data_Cleaning.ipynb` → Code notebook  
- `cleaned_preprocessed_dataset.csv` → Final cleaned dataset  
- `README.md` → Documentation  

## Author
Mohamed Shaaban Elshalakany  
Data Analysis Intern – Codveda Technologies
