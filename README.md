# Scoutify

- A project done for the course , Recommendation Systems.
- Note: We recommend running code only after reading the report.

# Description 

The ever-growing popularity of football has led to an increasing demand for efficient methods of player recruitment and team building. In this paper, we propose a novel recommendation system that leverages collaborative filtering techniques to provide personalized recommendations of football players to clubs. Our system aims to assist clubs in identifying potential players who align with their specific requirements and strategic objectives, thereby enhancing their chances of success on the field.\\
To build the recommendation system, we collected a comprehensive dataset comprising player attributes, performance statistics, and historical transfer information from various reliable sources. We employed collaborative and content based filtering and machine learning algorithms to extract meaningful patterns and capture player similarities based on their past performances and career trajectories. By leveraging both user-based and item-based collaborative filtering techniques, our system intelligently matches the preferences of clubs with the profiles of players to generate accurate and tailored recommendations.

# Live Demo
We recommend running the demo first, as it gives a simple UI to play with the parameters of the final model.
Google Collab Notebook Link: https://drive.google.com/file/d/19TccEUfcG0qiwyFkFtAtbIw7I5JdJo2I/view?usp=sharing

# Dependencies

- sklearn: scikit-learn library for machine learning tasks
- pandas: data manipulation library
- numpy: numerical computing library
- re: regular expression operations library
- plotly: plotting library for interactive visualizations
- plotly.graph_objects: graph objects module of Plotly for creating visualizations
- plotly.express: high-level interface of Plotly for creating visualizations
- math: mathematical functions library

# File Structure
- Dataset : This directory contains the original , official FIFA csv files containing all player information for the years 2017 -2023

## Final Models
- PlayerRec_actual.ipynb: Implementation of Approach-4 based on Clustering. This is our final model and is the backend for the demo.
- PlayerRec_extended.ipynb: Implementation of Approach-5 which extends approach-4 using XGBoost and Neural Networks.

## Initial Attempts
- nn.ipynb : This file includes some of our earlier approaches like KNN and using basic ML models on a basic definition of club philosophy.
- Bert approach: Recommended to run on google collab. https://drive.google.com/file/d/1ov39uAfohqIu2ZGAD0gV1W21nUvLWpzo/view?usp=sharing

## Synthesised Data 
- rec_actual_data: Contains data required to support the PlayerRec_actual.ipynb file. Mainly contains the synthesised Club Philosophy data.
- rec_extended_data : Contains data required to support PlayerRec_extended.ipynb file. Contains the Club_philosophy, player improvement data and trained XGBoost and NN Models.
- df_xx_improvement.csv : These are the modified dataframes that contain the additional columns which show the improvement shown by the player across two consecutive years. These support the nn.ipynb file.

# Instructions to Run
- All the mentioned Jupyter Notebooks can be directly run, given the required packages and helping data is available.


