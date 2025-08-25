Google Play Store Apps Dataset
Overview

This dataset contains information about apps available on the Google Play Store. It includes various attributes related to each app, such as name, category, rating, number of reviews, size, number of installs, type (free or paid), price, content rating, and genres.

Columns Description
Column	Description
App	Name of the application
Category	Category the app belongs to
Rating	Overall user rating of the app
Reviews	Number of user reviews
Size	Size of the app (e.g., 10M, 500K)
Installs	Number of user downloads/installs
Type	Free or Paid
Price	Price of the app in USD
Content Rating	Age group targeted (e.g., Everyone, Teen, Mature 17+)
Genres	Main genre and sub-genres (separated by ;)
Current Ver	Current version of the app
Android Ver	Minimum required Android version
Data Cleaning / Preprocessing Notes

Numeric conversion:

Size was converted to numeric by splitting units (e.g., 10M → 10000 KB).

Price was converted to float (removing $).

Installs was cleaned (removing + and ,) and converted to integer.

Rating converted to numeric, filtering out invalid outliers (>5).

Missing values:

Columns like Type, Content Rating, Current Ver, and Android Ver had missing values, handled by dropping or imputation when appropriate.

Outliers:

Price and Rating outliers were handled (e.g., log transformation for skewed distribution, or filtering unrealistic values).

Genres:

Some apps belong to multiple genres, separated by ;. The first value is the main genre, the second (if exists) is the sub-genre.

Potential Analysis / Use Cases

Identify the most expensive apps and their ratings.

Compare free vs paid apps in terms of size, price, and ratings.

Determine the estimated revenue for Google from high-install apps.

Explore app distribution across categories and content ratings.

Analyze correlation between Rating, Reviews, Size, and Price.

Example Visualizations

Bar charts for top apps by price or installs.

Boxplots comparing sizes or ratings of free vs paid apps.

Heatmaps to show correlation between numeric features.

Pie charts for distribution of app types or categories.
