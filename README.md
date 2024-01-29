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


### Training Listings DataFrame (train_listings_df)

The `train_listings_df` DataFrame is the primary dataset containing information about real estate listings. Here are the key details:

- **Columns**:
  1. `id` (float64): Unique identifier for each listing.
  2. `sourceId` (float64): Identifier for the source of the listing.
  3. `locationId` (float64): Identifier for the location of the listing.
  4. `typeId` (float64): Identifier for the type of property.
  5. `price` (float64): Price of the property.
  6. `rooms` (float64): Number of rooms in the property.
  7. `bedrooms` (float64): Number of bedrooms in the property.
  8. `bathrooms` (float64): Number of bathrooms in the property.
  9. `totalArea` (float64): Total area of the property.
  10. `livingArea` (float64): Living area of the property.
  11. `plotArea` (float64): Plot area of the property.
  12. `terraceArea` (float64): Terrace area of the property.
  13. `title` (object): Title of the listing.
  14. `description` (object): Description of the listing.
  15. `features` (object): Features associated with the listing.
  16. `latitude` (float64): Latitude of the property location.
  17. `longitude` (float64): Longitude of the property location.
  18. `thumbnails` (object): Thumbnails associated with the listing.
  19. `Unnamed: 18` to `Unnamed: 33`: Additional unnamed columns with mixed data types.

- **Summary**:
  - Total Entries: 83063
  - Several columns contain missing values.

This DataFrame serves as the foundation for analyzing and modeling real estate data.



# Cleaning dataste:
### trainListings.csv    
- Addressed shiffted records in Excel

# Python 
