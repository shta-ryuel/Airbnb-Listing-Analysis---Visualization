# Airbnb Listing Analysis and Visualization

## Project Overview
This project focuses on analyzing and visualizing data from an Airbnb dataset containing information about 12,800 listings worldwide. The dataset includes 23 columns, such as ratings, reviews, prices, and location details. The aim is to uncover insights about Airbnb listings and present them through meaningful visualizations.

## Dataset Details
The dataset consists of the following columns:
- `name`: Name of the Airbnb listing.
- `rating`: Average rating of the listing.
- `reviews`: Number of reviews received.
- `address`: Location of the listing (city, region, country).
- `features`: Summary of features (number of guests, bedrooms, beds, bathrooms).
- `amenities`: List of amenities provided.
- `price`: Price per night in the local currency.
- `country`: Country where the listing is located.
- `bathrooms`: Number of bathrooms.
- `beds`: Number of beds.
- `guests`: Number of guests the listing can accommodate.
- `bedrooms`: Number of bedrooms.

Link to original dataset: https://www.kaggle.com/datasets/ashishjangra27/airbnb-dataset

## Key Insights and Visualizations

### 1. Price Distribution by Country
A KDE plot was used to visualize the density of Airbnb prices by country, highlighting price variations across different regions.

### 2. Most Expensive Airbnb Listings
A bar plot showcased the top 10 most expensive Airbnb listings and their respective countries.

### 3. Countries with the Highest and Lowest Number of Listings
A bar plot visualized the countries with the most and least number of Airbnb listings, enabling easy comparison.

### 4. Scatter Plot: Reviews vs. Rating
A scatter plot analyzed the relationship between the number of reviews and the average rating for listings.

## Tools and Libraries
- **Python**: For data processing and visualization.
- **Pandas**: To manipulate and clean the dataset.
- **Seaborn**: For creating advanced visualizations.
- **Matplotlib**: For plotting and enhancing visualizations.

## How to Run the Analysis
1. Install the required Python libraries:
   ```bash
   pip install pandas seaborn matplotlib
   ```
2. Load the dataset into a DataFrame:
   ```python
   import pandas as pd
   df = pd.read_csv('airbnb_listings.csv')
   ```
3. Execute the provided code snippets for data cleaning, analysis, and visualization.

## Conclusion
This project provides a comprehensive analysis of Airbnb listings, showcasing trends in price distribution, top listings, and country-specific data. The visualizations offer valuable insights that can aid in understanding the global Airbnb market.

