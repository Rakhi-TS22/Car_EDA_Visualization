# Car_EDA_Visualization
# Automotive Dataset Exploration and Visualization

## Overview
This dataset contains automotive data including information about various attributes of different cars such as fuel efficiency, engine specifications, weight, acceleration time, year of manufacture, and brand origin. The dataset can be used for Exploratory Data Analysis (EDA) to gain insights into the characteristics of the cars and visualize relationships between different variables.

## Dataset Description
The dataset consists of the following columns:
- **mpg**: Miles per gallon (fuel efficiency)
- **cylinders**: Number of cylinders in the engine
- **cubicinches**: Engine displacement in cubic inches
- **hp**: Horsepower
- **weightlbs**: Weight of the car in pounds
- **time-to-60**: Time taken for the car to accelerate from 0 to 60 mph
- **year**: Year of manufacture
- **brand**: Brand or origin of the car (US or Europe)

## Exploratory Data Analysis (EDA)
To perform EDA on this dataset, you can explore various aspects such as:
- Distribution of each attribute
- Summary statistics for numerical variables
- Correlation between variables
- Trends over different years
- Comparison between US and European cars

## Visualization
Visualizations play a crucial role in understanding the data and uncovering patterns. Some visualizations that can be created from this dataset include:
- Histograms and density plots to visualize the distribution of numerical variables
- Scatter plots to explore relationships between variables such as mpg vs. weight, mpg vs. horsepower, etc.
- Box plots to compare distributions across different categories (e.g., cylinders, brand)
- Time series plots to observe trends in automotive characteristics over the years

## Getting Started
To start exploring and visualizing the dataset, you can use collab or Jupiternotebook. Simply load the dataset cars (1).csv into your environment and open the Cars_Visualization.ipynb"!

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load the dataset
data = pd.read_csv("cars (1).csv")

```

## Contributors
This dataset and initial analysis were contributed by Rakhi Tulaskar & Intellipaat.
