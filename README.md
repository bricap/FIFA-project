Project Overview
This project involves the analysis and modeling of FIFA 22 player data using Python. The main goals are to explore the dataset, perform statistical analysis, and build predictive models to understand player rankings and foot preferences. The project includes data cleaning, exploratory data analysis, regression modeling, and classification tasks.

Dataset
The dataset used in this project is fifa22.csv, which contains detailed information about FIFA 22 players. 

The dataset includes the following features:
name: Player's name
rank: Player's ranking
gender: Gender of the player
wage_eur: Player's wage in euros
log_wage: Log-transformed wage
position: Player's position on the field
nationality: Player's nationality
club: Player's club
league: League in which the player's club participates
preferred_foot: Player's preferred foot
shooting, passing, dribbling, defending, attacking, skill, movement, power, mentality, goalkeeping: Player's attributes in various skills
The dataset consists of 19,630 observations and 20 features.

Analysis and Modeling Breakdown
1. Exploratory Data Analysis
2. Regression Analysis
3. Predictive Modeling
4. Feature Scaling and Sampling

Standard Scaling:
Features were scaled using StandardScaler for better model performance.
Sampled 5000 observations for analysis.

Key Findings
The regression model explains a significant portion of the variability in player rankings, with attacking and defending being the most impactful features.
The linear regression model has a low prediction error, making it reliable for predicting player rankings.
The KNN classifier struggles to accurately predict left-footed players, indicating the need for further model tuning or alternative approaches.

Conclusion
The project demonstrates the use of various statistical and machine learning techniques to analyze and predict FIFA player data. 
The findings can help in understanding the key factors influencing player rankings and improving predictive models for player attributes.

Requirements:
Python 3.7+
Libraries: pandas, numpy, statsmodels, scikit-learn, matplotlib
