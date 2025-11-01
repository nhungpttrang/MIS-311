# MIS-311 — Cost of Living Project Insights 
## Data overview
The dataset “Cost of Living” contains 202 records across multiple countries and regions, with 5 columns: Country, Region, Year, Average Monthly Income, and Cost of Living.
It captures each country's average income and living cost in USD, providing a basis to analyze affordability and economic differences globally.
## Data cleaning 
Handling Missing Values:
- Average Monthly Income Column: As income is a core and non-inferable variable, I opted for Row Deletion for these 2 records, to prevent any skew in statistical calculations related to affordability.
- Region Column: I applied Manual Imputation. Based on the corresponding Country name, I assigned the correct region to these records, thereby preserving valuable data points.
  
Handling Duplicate rows:
- There are 4 duplicate values found and removed, to ensure that every observation in the dataset was unique and did not bias the analysis results.
## Descriptive Statistics
## Insight 1: Income and Cost of Living Have Almost No Correlation
<img width="858" height="442" alt="image" src="https://github.com/user-attachments/assets/2f6e8a48-9b6c-4729-9a80-8e6885533d67" />

The scatter plot shows that income and cost of living have almost no relationship, the trendline is almost flat (R² = 0.0007), which means when the cost of living increases, the income does not clearly increase or decrease. So, we cannot assume that "a high-cost location will also have high incomes."

## Insight 2: Average Income and Cost of Living by Region
<img width="363" height="241" alt="image" src="https://github.com/user-attachments/assets/f38545f1-79ab-4b64-bc34-929de8be7d02" />

<img width="1009" height="450" alt="image" src="https://github.com/user-attachments/assets/3e956f6c-b06a-4e5b-bc2a-9e34323fdc88" />


While all other regions show an average income higher than average cost of living, North America is stark contrast. In North America, the average income is $3,764 and the average cost of living is $3,740. On average, its population has the lowest potential for savings, with incomes just barely breaking even with expenses.
