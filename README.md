### README for Assignment 1: Data Cleaning and Summarizing

**Author:** Amay Viswanathan Iyer  
**Email:** s3970066@student.rmit.edu.au  
**Student ID:** s3970066

---

#### Overview:
This project focuses on **data cleaning and summarizing** using a dataset provided by UNICEF on **school-age digital connectivity**. The tasks involved are data preparation, exploration, and summarizing the key findings using **Python** and **Pandas**. This project was done using **Jupyter Notebook**.

---

### 1. Data Preparation (Task 1)
In this task, I prepared the dataset for further analysis by performing the following key steps:
- **Handling Missing Values**: I identified columns with missing data (`Rural (Residence)`, `Urban (Residence)`, `Poorest (Wealth quintile)`, and `Richest (Wealth quintile)`) and replaced the missing values with mean values calculated based on the corresponding **Region** of the country.
- **Data Type Conversion**: I converted percentage values, stored as strings, into numerical values for accurate analysis.
- **Regular Expressions**: I corrected the inconsistent formatting in the `Time period` column (such as values like "2562", "2076") using regular expressions to bring them within the correct range (2010-2019).
- **Saving Cleaned Data**: The cleaned data was saved into CSV files for further exploration and analysis.

### 2. Data Exploration (Task 2)
#### Task 2.1:
For this part, I chose the following columns to explore:
- **Nominal Value**: `Region`
- **Ordinal Value**: `Income Group`
- **Numerical Value**: `Total`

I created several visualizations:
- **Boxplots** and **Swarm plots** to analyze the `Total` percentage of school-age children with internet access based on different income groups and regions.
- **Histograms** to examine the spread of internet access percentages across the dataset.

#### Task 2.2:
I analyzed the top 10 countries with the highest percentages of school-age children with internet access. I compared the percentages across **Income Groups** and **Residence** (Rural/Urban). The results showed that **High Income countries** have a larger disparity between rural and urban internet access compared to **Upper Middle Income countries**.

#### Task 2.3:
I compared the internet access percentages between **Primary** and **Secondary** school children from the **Lower Middle Income** group. The results indicate that the spread of data for internet access is similar for both groups, with some regional disparities.

---

### 3. Report (Task 3)
The final report, named `report.pdf`, provides a detailed explanation of the cleaning, exploration, and summarizing processes. It also includes visualizations and in-depth analysis of the dataset.

---

### Key Files:
1. `assignment1.ipynb`: Jupyter notebook with Python code for data cleaning, processing, and visualization.
2. `report.pdf`: A detailed report of the data preparation, exploration, and findings.
3. Cleaned CSV files:
   - `Primary_cleaned.csv`
   - `Secondary_cleaned.csv`
   - `Total_Age_cleaned.csv`

### How to Run the Code:
1. Open the Jupyter Notebook file (`assignment1.ipynb`).
2. Ensure all necessary libraries (like `Pandas`, `Matplotlib`, `Seaborn`, etc.) are installed.
3. Run all cells to load the data, clean it, and generate the visualizations.

---
