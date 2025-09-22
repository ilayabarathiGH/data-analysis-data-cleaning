# Mall Customer Data Cleaning Project

## Overview
This project demonstrates a complete **data cleaning workflow** applied to a **mall customer dataset**. The goal is to clean and preprocess customer data to make it ready for analysis, segmentation, and predictive modeling.

## Dataset
The dataset contains information about mall customers, including:

- `CustomerID` – Unique identifier for each customer  
- `Gender` – Male or Female  
- `Age` – Age of the customer  
- `Annual Income (k$)` – Annual income in thousand dollars  
- `Spending Score (1-100)` – Customer spending score based on behavior  

## Cleaning Steps
1. **Handling Missing Values**  
   - Filled missing ages and income values with median  
   - Filled missing gender values with mode  

2. **Removing Duplicates**  
   - Checked for duplicate `CustomerID` entries and removed them  

3. **Standardizing Data**  
   - Standardized gender values (`male` → `Male`, `female` → `Female`)  

4. **Correcting Data Types**  
   - Ensured numerical columns are numeric and categorical columns are strings  

5. **Handling Outliers**  
   - Detected and treated outliers in `Age`, `Annual Income`, and `Spending Score` using IQR  

6. **Saving Cleaned Dataset**  
   - Cleaned data saved as `mall_customers_cleaned.csv`  

## Folder Structure
