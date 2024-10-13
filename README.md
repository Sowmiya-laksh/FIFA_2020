> # FIFA_2020
### Project Overview
This project aims to explore the skillsets of FIFA 20 football players, cluster them based on their attributes, and answer key football-related analytical questions. The analysis and clustering are designed to provide insights into player performance and country-based player production using the FIFA 20 dataset.

### Problem Statement
#### Task 1:
Prepare a complete data analysis report on the provided dataset.

#### Task 2:
Cluster football players based on their skill attributes and explore football skills using machine learning techniques.

#### Task 3:
Explore the dataset by answering the following questions:
- Prepare a rank-ordered list of the top 10 countries with the most players. Which countries produce the highest number of footballers playing at this level?
- Plot the distribution of overall rating vs. age of players. At what age do players stop improving?
- Which offensive players get paid the most: strikers, right-wingers, or left-wingers?

### Dataset Description
The dataset contains football players' data from the FIFA 20 video game, including their skill attributes, positions, and ratings. The attributes allow comparisons between players and analysis of player characteristics based on various features.

### Key Attributes:
- *Name*: Name of the player
- *Age*: Age of the player
- *Height*: Height of the player (in centimeters)
- *Overall*: General performance rating of the player (1-99)
- *Potential*: The maximum overall rating a player can reach (1-99)
- *PreferredFoot*: Indicates whether the player is left- or right-footed
- *WorkRate*: Represents the player's effort in attack and defense
- *Position*: The player's position on the field (e.g., striker, forward, winger)
- *Offensive and defensive skills*: Including attributes like Crossing, Finishing, Dribbling, SprintSpeed, Acceleration, Strength, Stamina, and more, which reflect the player's abilities and effectiveness in specific roles

### Solution Approach
- *Data Analysis and Preprocessing*: Clean and prepare the data for analysis, handle missing values, and encode categorical variables such as player positions and work rate.
- *Exploratory Data Analysis (EDA)*: Explore the dataset and visualize relationships between player attributes, such as the distribution of ratings by age and country, and assess player clusters.
- *Clustering Models*: Apply clustering algorithms (e.g., K-Means) to group players based on their skill attributes and identify trends in player performance.
- *Player Rankings and Analysis*: Generate rankings of top countries by player count and analyze the salary trends of different offensive positions.
  
### Challenges Faced
- *Handling Missing Data*: Some attributes may have missing or incomplete values, which were addressed during preprocessing.
- *Feature Selection*: Selecting the most relevant attributes for clustering and excluding redundant features to ensure meaningful player groups.
- *Clustering Optimization*: Identifying the optimal number of clusters that best represent player skill sets and analyzing these clusters to draw insights.
- *Data Imbalance*: Managing the imbalance between different countries producing football players and different player positions.

### Practice Skills
- Data preprocessing and feature engineering on a large dataset
- Clustering techniques (e.g., K-Means) to group players based on attributes
- Visualizing trends and relationships between player skills and age, position, or country
- Answering business questions through football-related data analysis

### Model Comparison Report
This section contains a comparison of clustering models and analysis of the clusters formed based on player attributes. A discussion on which clustering algorithm best captures player groupings is included.

### Conclusion
This project offers insights into football players' skills and positions using FIFA 20 data, helping understand trends in player development, salary distribution, and country-based player production.
