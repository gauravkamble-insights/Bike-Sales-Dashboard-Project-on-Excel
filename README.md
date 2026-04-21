# Bike Sales Dashboard Project on Excel

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Project Overview
This project demonstrates a comprehensive data analysis workflow in Excel, including data cleaning and the creation of an interactive dashboard. The primary goal was to analyze customer demographics and behaviors (such as income, age, and commute distance) to identify key trends in bike purchases.  

## Dataset Description
The [dataset](https://github.com/gauravkamble-insights/Bike-Sales-Dashboard-Project-on-Excel/blob/main/src/data/Bike%20Buyers%20Dataset.xlsx) includes several demographic and behavioral attributes of potential bike buyers:  
- **ID:** A unique identifier for each individual.  
- **Marital Status & Gender:** Standardized categories used for demographic analysis.  
- **Income:** The annual salary of the individuals.  
- **Education & Occupation:** The professional and educational background of customers.  
- **Commute Distance:** The distance an individual travels to work.  
- **Age:** Grouped into specific brackets for clearer visualization.  
- **Purchased Bike:** The target variable indicating if a purchase was actually made.  


## Data Cleaning and Transformation
To prepare the data for analysis, the following steps were taken:  
- **Removing Duplicates:** The data was cleansed of redundant entries to ensure accuracy.  
- **Find and Replace:** Standardized abbreviations in the Marital Status (M to Married, S to Single) and Gender (M to Male, F to Female) columns for better readability.  
- **Data Formatting:** Adjusted the Income column to a currency format with zero decimal places for a cleaner appearance.  
- **Age Bracketing:** Created a new column using nested IF statements to categorize ages into three brackets: Adolescent (under 31), Middle Age (31 through 54), and Old (55 and above).  
- **Commute Distance Refinement:** Modified labels for commute distances, such as changing "10+ miles" to "More than 10 miles," to ensure they sorted correctly in visualizations.  

## Dashboard Features
The [final dashboard](https://github.com/gauravkamble-insights/Bike-Sales-Dashboard-Project-on-Excel/blob/main/final_project/Complete%20Excel%20Project%20-%20Sales%20Dashboard.xlsx) was built using Pivot Tables and interactive visualizations:  
**1. Visualizations**  
- Average Income per Purchase: A bar chart comparing the income levels of those who did and did not purchase a bike, broken down by gender.  
- Customer Age Brackets: A line chart showing that middle-aged individuals (31 to 54) are the most frequent bike buyers.  
- Customer Commute: A visualization showing how commute distance impacts the likelihood of purchasing a bike, indicating higher sales for shorter commutes.
  
**2. Interactivity (Slicers)**
The dashboard includes three interactive Slicers that allow users to filter the entire view simultaneously:  
- Marital Status  
- Education  
- Region  


## Dashboard Preview
<img width="1123" height="651" alt="Dashboard" src="https://github.com/gauravkamble-insights/Bike-Sales-Dashboard-Project-on-Excel/blob/main/assets/Dashboard.png" />

## Key Insights
- **Income:** On average, individuals with higher incomes (roughly $55,000 to $60,000) were more likely to purchase a bike compared to those with lower average incomes.
- **Age Demographics:** The Middle Age segment represents the peak customer base for bike sales, while those under 31 buy significantly fewer bikes.
- **Commute:** Customers with the shortest commutes (0 to 1 miles) showed the highest volume of bike purchases.

## How to Use
1. Download the .xlsx file from this repository.
2. Open the file in Microsoft Excel.
3. Navigate to the Dashboard sheet.
4. Use the Slicers on the left to filter the data by Marital Status, Education, or Region.

## Author
- <b>©2026 Gaurav Kamble.  
- <b>[LinkedIn](https://www.linkedin.com/in/gaurav-kamble/)</b>
- <b>[Tableau Public](https://public.tableau.com/app/profile/datagaurav/vizzes)</b>
- <b>[Kaggle](https://www.kaggle.com/justgk)</b>
- <b>[Email](mailto:gauravksse@gmail.com)</b>
