# Google Play Store Apps Analysis

## Overview
The Play Store hosts a wide range of applications, and the data associated with these apps offers significant potential for analysis. Developers and businesses can leverage this data to understand market trends, optimize their apps, and maximize user engagement. 
In this project, we will perform a data cleaning and preprocessing task on the Play Store apps dataset, addressing missing values, outliers, and other issues while extracting valuable insights.


## Dataset Description
The dataset contains information about apps available on the Google Play Store, including:

- **App**: Name of the application
- **Category**: Category the app belongs to
- **Rating**: Overall user rating
- **Reviews**: Number of user reviews
- **Size**: Size of the app (e.g., 10M, 500K)
- **Installs**: Number of user downloads/installs
- **Type**: Free or Paid
- **Price**: Price of the app in USD
- **Content Rating**: Age group targeted (e.g., Everyone, Teen)
- **Genres**: Main genre and sub-genres (separated by `;`)
- **Current Ver**: Current version of the app
- **Android Ver**: Minimum required Android version

## Data Cleaning / Preprocessing
- Converted `Size`, `Price`, `Installs`, and `Rating` to numeric values after cleaning.  
- Handled missing values in columns like `Type`, `Content Rating`, `Current Ver`, and `Android Ver`.  
- Removed outliers in `Rating` and `Price`.  
- Split `Genres` into main and sub-genres (separated by `;`).  

## Analysis / Visualizations
- Top apps by price and rating.  
- Free vs. Paid app comparison (size, price, ratings).  
- Estimated revenue from apps with high installs.  
- Correlation between `Rating`, `Reviews`, `Size`, and `Price`.    

## Example Visualizations
- Bar charts for top apps by price or installs.  
- Heatmaps showing correlations between numeric features.  
- Pie charts for distribution of app types or categories.

