# Power-BI-FINOPPS-ANAlYSIS

## Table Of Contents

- [Project Overview](#Project Overview)

### Project Overview

This project seeks to deliver insights for FINOPPS by comparing PAYG Rates with CSP Rates, aiming to determine whether transitioning to a CSP would be more advantageous than staying with the PAYG Rate.


### Data Source
FINOPPS Data:A csv file provided by the organisation ,which contains the relevant data for analysis and comparison.

### Tools
- Power BI : Data Extraction ,Data Cleaning, Data Modelling, Data Visualisation.


### Data Extraction and Cleaning
1. Extract the CSV file (FINOPPS Data) into Power BI.
2. Load and transform the data using Power Query.
3. Address any missing values.
4. Standardize data formatting.

### Data Modelling
1. Identify and count the number of dimension tables (Dim Tables) derived from the Fact Table (FINOPPS Data).
2. Duplicate the Fact Table based on the identified number of Dimension Tables.
3. Create the necessary Dimension Tables.
4. Normalize the Fact Table and rename it to FactFinopps, then close Power Query.


### Data Modelling
1. Navigate to the modeling page by clicking the leftmost option on the home tab.
2. Establish a Star Schema model by creating relationships between the Fact Table and the Dimension Tables.
3. Use the drag-and-drop method to define these relationships.

   [Star Schema]


### Data Visualisation
1. Create a DAX Measure Table containing calculations for CSP Rate and PAYG Rate for report visualizations (for comparisons).
2. Design the report theme.
3. Select appropriate visualizations and format them according to the theme.
4. Conduct testing on the report.

### Explanatory Data Analysis
- Analyze costs per subscriptionName, MeterCategory, and ResourceGroup.
- Assess potential savings/costs using the CSP Rate.

### Findings
- The Finopps Core Production Subscription represents the highest liability to the organization when using the PAYG Rate.
- Transitioning to CSP yields significant savings for the company.

### Recommendation
1. I recommend the company switch to the CSP Rate, as it demonstrates a substantial reduction in costs compared to PAYG.
2. Increase the use of compute engines over storage to further minimize expenses.
