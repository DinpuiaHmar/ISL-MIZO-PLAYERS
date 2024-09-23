# Indian Super League Mizo Players Analysis

This project analyzes Mizo players currently playing in the Indian Super League (ISL) 2024. It involves data scraping from [Transfermarkt](https://www.transfermarkt.co.in/) and [Inkhel](https://www.inkhel.com/) to gather statistics such as age, position, market value, and place of birth. The project then performs detailed data analysis and visualizations using Python, Seaborn, and Matplotlib.

## Data Overview

The dataset includes the following columns:
- **Name**: Player's full name
- **Club**: The ISL club where the player currently plays
- **Position**: The role of the player (Goalkeeper, Defender, Midfielder, Forward)
- **Age**: The age of the player
- **Place of Birth**: The city or district of birth
- **Market Value**: The player's current market value in INR
- **Age Group**: Categorized age groups for better analysis

## Features of the Project

### 1. **Data Cleaning**
- Replaced missing and inconsistent values in columns like `Place of Birth` and `Market Value`.
- Converted and standardized numerical columns for accurate analysis.

### 2. **Data Analysis**
- **Player Distribution**: A count of players by club, position, and place of birth.
- **Age Group Analysis**: Categorization and analysis of players into different age groups (20 and below, 21-25, 26 and above).
- **Market Value**: Basic statistics like mean, median, range, variance, and standard deviation of market values.
  
### 3. **Visualization**
- Created interactive and attractive visualizations to showcase insights using Seaborn and Matplotlib.
- **Club-wise Player Distribution**: Visualized the number of players in each club.
- **Position-wise Player Count**: Counted players by position (Goalkeeper, Defender, Midfielder, Forward).
- **Age Group Distribution**: Displayed players' age distribution in categorized groups.
- **Market Value Analysis**: Used histograms and box plots to analyze the distribution of market values.

### 4. **Statistical Analysis**
- **Mean and Standard Deviation** of player ages to show the variation within the dataset.
- Calculated **Mean, Median, Range, Variance, and Standard Deviation** of market values to assess the financial worth of players.

## Libraries Used

- **Pandas**: For data manipulation and analysis
- **Seaborn**: For generating attractive visualizations
- **Matplotlib**: For plotting and visual representation
- **Statistics**: For basic statistical calculations

## Conclusion

This project provides insights into Mizo players' performance, distribution, and financial worth in the ISL 2024. It offers both statistical and visual analysis, making it accessible and easy to understand for audiences interested in football analytics.
