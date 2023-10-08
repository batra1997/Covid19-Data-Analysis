# Covid19-Data-Analysis

## Data Collection: 
The analysis involved the collection of COVID-19 data using publicly available datasets on Data Catalogue that are <Confirmed_Cases.csv>(https://data.ontario.ca/dataset/confirmed-positive-cases-of-covid-19-in-ontario/resource/455fd63b-603d-4608-8216-7d8647f43350)
 and Vaccination_Data.xls

## Data Preprocessing: 
The collected data underwent preprocessing steps, including data cleaning that involved -:
### Confirmed_Cases.csv Python Analysis
•	Handling missing values in the Outcome1(later renamed to Severity) column
•	Formatting the datatype to datetime for Case_Reported_Date column
•	Adding column for Year in the dataset separately for analysis

### Vaccination_Data.xls Excel Analysis
•	The non-zero values from fully vaccinated column were moved to second column cumulative.

## Data Reduction: 
Data reduction techniques were applied to extract the necessary information for analysis. This included -: 
•	Selecting specific columns (Age_Group, Reporting_PHU_City, Client_Gender, Severity, Case_Reported_Date) and removing the columns not required for analysis
•	Removing rows filtered on Client_Gender, Age_Group and Year column

## Data Analysis: 
Python's data analysis libraries, such as pandas, NumPy, and Matplotlib/Seaborn for visualization, were used to perform various analysis, including -:

•	Descriptive statistics to understand data characteristics.
•	Data visualization (line plots, bar charts, Heatmap) to visualize trends.
•	The Vaccination_Data dataset was first studied on how the records have been maintained. It was then seen that starting 1 Dec 2022 , the data has been recorded under fully vaccinated column, rather than second dose cumulative column.

# Tools Used:

Programming Language – Python
Development Environment – Jupyter Notebook(IDE) – Confirmed_Cases dataset
				                  Microsoft Excel – Vaccination_Data Dataset

# Summary:

COVID-19 data analysis was conducted using two separate tools: Python and Excel. Python was used for its flexibility in data collection, preprocessing, and advanced analysis techniques, while Excel was employed for its user-friendly interface and data reduction capabilities. Both tools contributed to extracting valuable insights from COVID-19 datasets for reporting and decision-making.
