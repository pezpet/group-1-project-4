**Question**
Our team's question: "How likely is it that a hate crime will face prosecution given the specific characteristics and the demographics of the county where it occurred?

*Please refer to the executive summary for greater detail about our question

**Table of Contents**
1. code/
    1. Data Cleaning
    2. Exploratory Data Analysis (EDA)
    3. EDA maps
    4. Models (excluding Neural Networks)
    5. Neural Network Model
    6. Neural Network Model with Grid Searching
2. data/
    1. Base Data
    2. Demographics Data
    3. Modeling data
3. plots/
4. presentation/
5. scratch/
6. Executive Summary Report
7. README.md

**Executive Summary**
Please refer to the "link" for the executive summary
<a href = "https://github.com/pezpet/group-3-project-4/blob/main/Executive%20Summary.md">Executive Summary</a>

**Data Description**
Please refer to the "Data Dictionary" section with the executive summary

**Data Cleaning**
- Demographics data was cleaned of all erroneous values and formatted. Columns renamed.
- Hate Crimes data 'County' and 'Agency' columns were mapped according to code numbers from the code book. Missing values filled.
- Prosecution data cleaned of all erroneous values (e.g. "-" instead of 0). Reformatted to integers. County names normalized and all data was grouped and aggregated by county, thus adding data for all years together.
- Prosecution rates were calculated for each county as Total Dispositions / Total Hate Crime Cases Referred. THIS IS OUR TARGET VARIABLE.
- Demographics data was added to each county in Hate Crimes and/or Prosecution DataFrames where relevant, thus creating Main DataFrames.
- Files were saved in data folder.


