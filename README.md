# Covid19-Data-Analysis

## Data Collection: 
The analysis involved the collection of COVID-19 data using publicly available datasets on Data Catalogue that are [Confirmed_Cases.csv](https://data.ontario.ca/dataset/confirmed-positive-cases-of-covid-19-in-ontario/resource/455fd63b-603d-4608-8216-7d8647f43350) and [Vaccination_Data.xls](https://data.ontario.ca/dataset/covid-19-vaccine-data-in-ontario/resource/2a362139-b782-43b1-b3cb-078a2ef19524)

## Data Preprocessing: 
The collected data underwent preprocessing steps, including data cleaning that involved -:<br>

### Confirmed_Cases.csv Python Analysis<br>
• Handling missing values in the Outcome1(later renamed to Severity) column<br>
• Formatting the datatype to datetime for Case_Reported_Date column<br>
• Adding column for Year in the dataset separately for analysis<br>

### Vaccination_Data.xls Excel Analysis<br>
• The non-zero values from fully vaccinated column were moved to second column cumulative.<br>

## Data Reduction:<br>
Data reduction techniques were applied to extract the necessary information for analysis. This included -:<br>
• Selecting specific columns (Age_Group, Reporting_PHU_City, Client_Gender, Severity, Case_Reported_Date) and removing the columns not required for analysis<br>
• Removing rows filtered on Client_Gender, Age_Group and Year column<br>

## Data Analysis:<br>
Python's data analysis libraries, such as pandas, NumPy, and Matplotlib/Seaborn for visualization, were used to perform various analysis, including -:<br>
• Descriptive statistics to understand data characteristics.<br>
• Data visualization (line plots, bar charts, Heatmap) to visualize trends.<br>
• The Vaccination_Data dataset was first studied on how the records have been maintained. It was then seen that starting 1 Dec 2022 , the data has been recorded under fully vaccinated column, rather than second dose cumulative column.<br>

# Tools Used:<br>

Programming Language – Python<br>
Development Environment – Jupyter Notebook(IDE) – Confirmed_Cases dataset<br>
				                  Microsoft Excel – Vaccination_Data Dataset<br>

# Summary:<br>

COVID-19 data analysis was conducted using two separate tools: Python and Excel. Python was used for its flexibility in data collection, preprocessing, and advanced analysis techniques, while Excel was employed for its user-friendly interface and data reduction capabilities. Both tools contributed to extracting valuable insights from COVID-19 datasets for reporting and decision-making.
