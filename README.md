# USA County Dataset Analysis

This repository contains the analysis of the USA County dataset, focusing on various geographic and demographic aspects of counties in the United States. The dataset includes information about the county's founding, population, land area, and water area, among other features. This analysis involves data cleaning, transformations, and visualization using Python libraries such as Pandas, NumPy, Seaborn, and Missingno.

## Dataset Overview

The dataset provides details on 3245 counties across the United States, with the following columns:

- **county**: The name of the county.
- **state**: The state to which the county belongs.
- **founded**: The founding date of the county.
- **largest_city**: The largest city in the county.
- **pop_total**: The total population of the county.
- **pop_den**: Population density per square mile and per square kilometer.
- **total_area**: Total area of the county in square miles and kilometers.
- **land_area**: Land area of the county in square miles and kilometers.
- **water_area**: Water area of the county in square miles and kilometers.

## Libraries Used

- **NumPy**: Used for numerical computations and data manipulations.
- **Pandas**: Used for data analysis and manipulation.
- **Seaborn**: For data visualization and creating plots.
- **Scikit-learn**: For machine learning and statistical modeling.
- **Missingno**: For visualizing missing data in the dataset.

## Data Cleaning and Transformation

1. **Splitting Columns**: The `pop_den`, `total_area`, `land_area`, and `water_area` columns contained combined units in both square miles (sq mi) and square kilometers (km). These columns were split into two separate columns for better clarity and usability.
   
2. **Removing Unnecessary Columns**: Columns that are not needed for the analysis (e.g., `founded`) were dropped from the dataset.

3. **Handling Missing Data**: Missing values were handled using `Missingno` to visualize and analyze the gaps in the dataset.

## Data Analysis

The cleaned dataset is now ready for further analysis, which can include:
- Population density trends across states and counties.
- Comparative analysis of county sizes (land vs. water area).
- Visualization of the most and least populated counties.
- Correlations between county size and population density.

