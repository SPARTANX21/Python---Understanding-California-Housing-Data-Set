# **California Housing Data Analysis**

![California Housing](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVZ-7EdlYj9C-ktjeVqqO9acDrYtiIKPALvw&usqp=CAU)

![Data Science](https://img.shields.io/badge/Data%20Science-Exploration%20%7C%20Cleaning%20%7C%20EDA%20%7C%20FeatureEngineering-blue)
![Python](https://img.shields.io/badge/Language-Python%203.11.9-yellow)
## Introduction

Welcome to the California Housing Data Analysis project! In this project, we delve into a comprehensive dataset containing information about housing in various block groups across California. The dataset provides metrics such as population, median income, median housing prices, and more.

### Dataset Overview

The dataset includes the following features:

- **Geographical Information:**
  - Latitude
  - Longitude

- **Housing Details:**
  - Housing Median Age
  - Total Rooms
  - Total Bedrooms
  - Households

- **Population Details:**
  - Population

- **Income and Value Metrics:**
  - Median Income
  - Median House Value

- **Categorical Information:**
  - Ocean Proximity

### Feature Types

- **Nominal Features:**
  - Latitude
  - Longitude
  - Ocean Proximity

- **Ordinal Features:**
  - Housing Median Age

- **Continuous Features:**
  - Median House Value
  - Median Income
  - Median Age

- **Discrete Features:**
  - Population
  - Number of Rooms and Bedrooms

### Project Structure

1. **Exploratory Data Analysis (EDA):**
   - Calculate and visualize the average median income.
   - Explore the distribution of housing median age.

2. **Visualization:**
   - Examine the relationship between median income and median house values through visualization.

3. **Data Cleaning:**
   - Create a dataset by removing entries with missing total bedrooms.
   - Create a dataset by filling in missing total bedroom values with the mean.

4. **Statistical Analysis:**
   - Develop a user-defined function to calculate the median value for selected columns.

5. **Geospatial Analysis:**
   - Plot latitude versus longitude to visualize the geographical distribution.

6. **Subset Creation:**
   - Form a dataset containing entries with 'Near Ocean' as the ocean proximity.

7. **Mean and Median Calculation:**
   - Calculate the mean and median of the median income for the 'Near Ocean' dataset.

8. **Feature Engineering:**
   - Introduce a new column, 'total_bedroom_size,' based on total bedrooms.

### Project Flow

The project progresses from data exploration to cleaning and advanced analysis, incorporating geospatial representation and feature engineering. Each step is documented with clear explanations and visualizations to facilitate understanding.

### Requirements

Ensure you have the required libraries installed by running:

```bash
pip install pandas numpy seaborn matplotlib
```

### Installation Instructions

Before getting started, ensure you have the required Python libraries installed by running the following command:

```bash
pip install pandas numpy seaborn matplotlib
```

### How to Use

1. Clone this repository to your local machine by executing the following command in your terminal:

   ```bash
   git clone https://github.com/SPARTANX21/Python---Understanding-California-Housing-Data-Set.git
   ```

2. Navigate to the project directory using the terminal:

   ```bash
   cd Python---Understanding-California-Housing-Data-Set.git
   ```

3. Launch Jupyter Notebook to access the project files and execute the analysis:

   ```bash
   jupyter notebook
   ```

Follow these steps to explore and analyze the California Housing Data Set efficiently. Should you have any questions or suggestions, feel free to reach out or open an issue on the repository.

Happy analyzing! 🏡📊
