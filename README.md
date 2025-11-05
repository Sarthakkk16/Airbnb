![](https://github.com/Sarthakkk16/Airbnb/blob/main/Airbnb-Logo-Contest-830x400.png)
# *Airbnb*
This project analyzes Airbnb listings in New York City to uncover pricing trends, host behavior, availability patterns, and geographical insights. Using Python’s data analysis and visualization libraries, we explore how different factors such as location, room type, and number of reviews influence rental prices.

## Dataset
The dataset contains **20,765 entries and 22 features**, including:
- **id**: Unique identifier for each listing  
- **name**: Title of the Airbnb listing  
- **host_name**: Name of the host  
- **neighborhood_group**: Group (borough) where the listing is located  
- **latitude/longitude**: Geolocation of listings  
- **price**: Nightly rental price  
- **room_type**: Type of accommodation (e.g., entire home, private room)  
- **reviews_per_month**: Average monthly reviews for the listing  
- **availability_365**: Number of available days in the year
- 
# 🧠 Objectives

- Perform data cleaning and handle missing/duplicate values
- Conduct univariate and bivariate analysis
- Visualize relationships between price, reviews, and availability
- Explore geographical distribution of listings
- Identify neighborhoods and room types with highest average prices

#  📑 Libraries
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns
- import warnings
 warnings.filterwarnings('ignore')
- %matplotlib inline

# 📊 Key Analysis Performed
### Univariate Analysis

- Price Distribution (sns.histplot, sns.boxplot)
- Number of Reviews and Availability across listings

### Bivariate Analysis

- Relationship between price and reviews
- Price vs. neighbourhood_group and room_type
- Correlation heatmap between numerical variables
### Geographical Analysis

- Mapped latitude vs. longitude by room type to visualize Airbnb density
- Found that Manhattan and Brooklyn dominate listings
