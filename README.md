# **Real Estate Data Analysis Project**

## Overview   

The Real Estate Data Analysis Project is an exploration and analysis of real estate listings, with a specific emphasis on predicting the totalArea of properties using regression methods. This project aims to build and evaluate regression models that capture the relationship between various features and the target variable totalArea. By employing regression techniques, I seek to provide estimations of property sizes based on key property features.

## Prerequisites
- [Google Colab](https://colab.research.google.com/): For executing Python code in a collaborative environment.
- [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel): For data exploration and manipulation.
- [Python Libraries](#python-libraries): Install the required Python libraries: pandas, sklearn, 

## Data Overview

### Locations DataFrame (locations_df)

The `locations_df` DataFrame contains information about locations. Here are the details:

- **Columns**:
  1. `id` (int64): Unique identifier for each location.
  2. `parentId` (int64): Identifier of the parent location.

- **Summary**:
  - Total Entries: 826
  - Non-Null Counts: All columns have 826 non-null entries.
  - Data Types: Both columns are of integer type.

This DataFrame is a fundamental part of the dataset, providing details about the hierarchical structure of locations.


### Types DataFrame (types_df)

The `types_df` DataFrame contains information about property types. Here are the details:

- **Columns**:
  1. `id` (int64): Unique identifier for each property type.
  2. `groupName` (object): Name of the property type.

- **Summary**:
  - Total Entries: 15
  - Non-Null Counts: All columns have 15 non-null entries.
  - Data Types: `id` is of integer type, and `groupName` is of object type.

This DataFrame provides insights into the different property types present in the dataset.




# Cleaning dataste:
### trainListings.csv    
- Addressed shiffted records in Excel

# Python 
