# Raw Sales Dataset

## Overview

The Raw Sales Dataset contains real estate transaction data.
Each row represents a property sale, including information about
when the property was sold, its price, location, and property characteristics.

This dataset can be used for:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Time-series trend analysis
- Building regression models to predict property prices


## Dataset Features

### 1. datesold
- The date when the property was sold.
- Format: YYYY-MM-DD
- Useful for analyzing trends over time.

### 2. postcode
- The postal code of the property location.
- Represents the geographic area.
- Can be used to group and compare regions.

### 3. price
- The sale price of the property.
- Numeric variable.
- Typically used as the target variable in prediction models.

### 4. propertyType
- The type of property sold (e.g., house, unit).
- Categorical variable.

### 5. bedrooms
- Number of bedrooms in the property.
- Numeric variable.
- Often related to property price.


## Dataset Structure

- Each row represents one property sale.
- The dataset contains 5 main columns.
- Suitable for regression analysis and visualization tasks.


## Possible Analysis

- Price distribution analysis
- Sales trends over time
- Revenue comparison by postcode
- Comparison between property types
- Price prediction using machine learning
