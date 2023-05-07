# Scoutify

A project done for the course , Recommendation Systems.

# Description 

The ever-growing popularity of football has led to an increasing demand for efficient methods of player recruitment and team building. In this paper, we propose a novel recommendation system that leverages collaborative filtering techniques to provide personalized recommendations of football players to clubs. Our system aims to assist clubs in identifying potential players who align with their specific requirements and strategic objectives, thereby enhancing their chances of success on the field.\\
To build the recommendation system, we collected a comprehensive dataset comprising player attributes, performance statistics, and historical transfer information from various reliable sources. We employed collaborative filtering and machine learning algorithms to extract meaningful patterns and capture player similarities based on their past performances and career trajectories. By leveraging both user-based and item-based collaborative filtering techniques, our system intelligently matches the preferences of clubs with the profiles of players to generate accurate and tailored recommendations.

# Live Demo

**insert colab link here*

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

Dataset : This directory contains the original , official FIFA csv files containing all player information for the years 2017 -2023

Models : This directory contains some of the saved models used for recommendations.

preds: 

rec_extended_data : Contains weights for each postition used in club philosophy. Also contains consolidated club philosophy.

PlayerRec.ipynb :  This file contains the final approaches used by us. This involves a clustering based approach and a an approach that uses XGBoost and neural networks. These 2 approaches use a complex formulation of club philosphy.

nn.ipynb : This file includes some of our earlier approaches like KNN , Bert and using basic ML models on a basic definition of club philosophy. 

df_xx_improvement.csv : These are the modified dataframes that contain the additional columns which show the improvement shown by the player across two consecutive years. 





