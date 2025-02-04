# Recreation Score Clustering Analysis

This repository contains the Jupyter Notebook `rec_score_cluster.ipynb`, which is dedicated to analyzing the clustering of real estate data based on recreation scores and trail proximity in Auburn, California.

## Project Overview

The analysis explores how the proximity to trails (trailhead score) affects real estate prices. The notebook includes detailed statistical analyses and regression models to predict housing prices based on these scores. It also visualizes the geographic distribution of these properties and their clustering based on the k-means and heirarchial clustering algorithms.

## Features

- **Data Preprocessing:** Clean and prepare the real estate data.
- **Statistical Analysis:** Conduct Ordinary Least Squares (OLS) regression to understand the impact of trailhead scores on real estate prices.
- **Clustering:** Apply k-means and heirarchial clustering to categorize properties based on their recreation score.
- **Visualization:** Map the clusters using geographical data to visualize the distribution and grouping of properties in relation to their proximity to trailheads.

## Technologies Used

- Python 3
- Pandas for data manipulation
- Statsmodels for regression analysis
- Scikit-learn for clustering
- Matplotlib and Contextily for visualizations
- Geopandas for geographical data handling

## Setup and Installation

Ensure you have Python 3.x installed along with Jupyter Notebook. You can install all required packages using the following command:

```bash
pip install numpy pandas matplotlib statsmodels scikit-learn geopandas contextily
