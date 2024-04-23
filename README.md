# EAFC-EDA
Exploratory Data analysis of all the players in game and ML 
# Football Player Analysis
This project focuses on analyzing and visualizing data related to football (soccer) players. The dataset used contains various attributes of football players, including their personal information, performance stats, preferred foot, and more. The aim is to gain insights into player performance, positional distribution, and other relevant factors.

Prerequisites
Python 3
Required Python libraries: pandas, matplotlib, seaborn, plotly, scikit-learn
Install the required libraries using pip:

pip install pandas matplotlib seaborn plotly scikit-learn
Getting Started
Clone the repository:
git clone https://github.com/MehParashar/EAFC-EDA.git
Navigate to the project directory:
cd EAFC-EDA
Run the Python scripts to analyze and visualize the football player data.
File Descriptions
all_players.csv: Dataset containing information about football players.
EAFC.ipynb: Jupyter Notebook containing the Python code for data analysis.
README.md: This file providing an overview of the project.
Analysis and Visualization
1. Basic Data Exploration
Load the dataset and display basic information.
Summary statistics of numerical features.
Count the number of missing values in each column.
2. Player Distribution
Distribution of player positions.
Distribution of player ages.
Distribution of player overall ratings.
Distribution of player preferred foot.
Distribution of player gender.
Distribution of player positions by gender.
3. Goalkeeper Analysis
Distribution of goalkeeper ratings.
Distribution of goalkeeper ratings by gender.
4. Correlation Analysis
Correlation between various player attributes and overall ratings.
Age vs. Overall Rating.
5. Positional Analysis
Average stats across different player positions.
National Team Strength: Average overall rating by nationality.
6. Machine Learning
Player Position Prediction
Trained a Random Forest classifier to predict player positions based on their attributes.
Achieved accuracy: 74%
Building a Dream Team
Implemented K-Means clustering to group players with similar attributes.
Formed a dream team by selecting the best player in each cluster based on overall rating.
Usage
The Jupyter Notebook analyze_players.ipynb contains the code for all the analyses and visualizations. Run the notebook using Jupyter Notebook or JupyterLab.

Acknowledgements
The dataset used in this project is sourced from [(https://www.kaggle.com/datasets/nyagami/fc-24-players-database-and-stats-from-easports)].
