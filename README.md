# Instagram Reach Analysis

![Instagram Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/1200px-Instagram_logo_2016.svg.png)

## Project Overview

This project analyzes Instagram post reach data to understand what factors contribute to higher engagement and reach. The analysis includes:

- Exploration of different sources of impressions (home, hashtags, explore, etc.)
- Relationship between impressions and engagement metrics (likes, comments, shares)
- Word cloud analysis of hashtags and captions
- Predictive modeling for reach

## Key Features

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Visualization of key metrics
- Predictive modeling using PassiveAggressiveRegressor
- Hashtag and caption analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- WordCloud
- Scikit-learn

## Dataset

The dataset (`Instagram data.csv`) contains metrics for 119 Instagram posts including:
- Impressions from various sources (home, hashtags, explore, other)
- Engagement metrics (saves, comments, shares, likes, profile visits, follows)
- Captions and hashtags used

## How to Run

1. Clone this repository
2. Install required packages (see requirements.txt)
3. Run the Jupyter notebook `Instagram_Reach_Analysis.ipynb`

## Future Enhancements

- Add more advanced predictive models
- Implement sentiment analysis on captions
- Create a dashboard for visualization
- Analyze optimal posting times
