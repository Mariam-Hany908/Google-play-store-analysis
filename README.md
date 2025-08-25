# Google Play Store Apps Analysis

## Overview
This project analyzes the Google Play Store apps dataset to explore app characteristics, pricing, ratings, and user engagement. It includes data cleaning, preprocessing, and visualization to identify trends, top apps, and estimated revenue insights.

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
- Distribution of apps across categories and content ratings.

## Potential Insights
- Identify trends in app pricing and popularity.  
- Discover which categories have the most highly-rated or expensive apps.  
- Estimate Google’s revenue from top-installed apps.  

## Example Visualizations
- Bar charts for top apps by price or installs.  
- Boxplots comparing sizes or ratings of free vs paid apps.  
- Heatmaps showing correlations between numeric features.  
- Pie charts for distribution of app types or categories.

