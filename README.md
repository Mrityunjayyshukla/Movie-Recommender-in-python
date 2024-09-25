# Movie Recommendation System

## Overview
This Movie Recommendation System is built in Python using content filtering techniques to recommend movies similar to those a user has already watched. It utilizes various libraries such as NumPy, Pandas, Matplotlib, Seaborn and FuzzyWuzzy, for data manipulation, analysis, and visualization.

## Features
- Recommends movies based on content filtering
- Utilizes user ratings and movie metadata
- Visualizes data using Matplotlib and Seaborn
- Implements fuzzy matching for better movie title matching

## Libraries Used
- **NumPy**: For numerical operations and data manipulation.
- **Pandas**: For handling and analyzing datasets.
- **Matplotlib**: For plotting and visualizing data.
- **Seaborn**: For enhanced data visualization.
- **FuzzyWuzzy**: For string matching to improve movie title recommendations.

## Datasets
The program uses two datasets:
1. **Ratings Dataset**: Contains columns `user_id`, `item_id`, `rating`, and `timestamp`. This dataset is used to track user preferences.
2. **Movies Dataset**: Contains columns `item_id` and `title`. This dataset provides the titles of the movies to be recommended.

## Installation
To run this program, make sure you have Python installed, along with the required libraries. You can install the necessary libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn fuzzywuzzy
