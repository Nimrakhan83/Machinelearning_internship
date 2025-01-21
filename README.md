# Restaurant Insights and Recommendation System

## Overview

This project involves building a set of machine learning models and tools to analyze restaurant data. It includes predicting restaurant ratings, creating a recommendation system, classifying restaurants based on their cuisines, and performing location-based analysis. The dataset is preprocessed, and various machine learning techniques are implemented to achieve these objectives.

---

## Features

1. **Predict Restaurant Ratings**  
   - **Objective**: Predict aggregate ratings based on features like cuisines, location, and price range.  
   - **Models**: Decision Tree Regressor, Linear Regression.  
   - **Metrics**: Mean Squared Error, R-squared.

2. **Restaurant Recommendation System**  
   - **Objective**: Recommend restaurants based on user preferences (e.g., cuisine, price range).  
   - **Technique**: Content-based filtering using cosine similarity.

3. **Cuisine Classification**  
   - **Objective**: Classify restaurants based on their cuisines.  
   - **Model**: Random Forest Classifier.  
   - **Metrics**: Accuracy, Precision, Recall, F1-score.

4. **Location-Based Analysis**  
   - **Objective**: Perform a geographical analysis of the restaurants in the dataset.  
   - **Steps**:  
     - Explore the latitude and longitude coordinates of the restaurants and visualize their distribution on a map.  
     - Group the restaurants by city or locality and analyze the concentration of restaurants in different areas.  
     - Calculate statistics such as the average ratings, cuisines, or price ranges by city or locality.  
     - Identify any interesting insights or patterns related to the locations of the restaurants.  
   - **Tools**: Geopandas, Folium, Matplotlib.

---

## Dataset

- **Source**: [Dataset.xlsx](https://www.kaggle.com/input/ml-intern/Dataset.xlsx)
- **Description**: Includes details like restaurant names, locations, cuisines, price range, aggregate ratings, and more.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/restaurant-insights.git
