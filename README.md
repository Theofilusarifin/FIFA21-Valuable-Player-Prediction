# FIFA21 Valuable Player Prediction

## Overview:
This project aims to predict valuable players in FIFA21 using machine learning techniques. In the world of professional soccer, identifying valuable players is crucial for clubs in building successful teams and making strategic decisions in player recruitment and management. By leveraging data analysis and machine learning, this project provides insights into player valuation and helps clubs identify undervalued players with high potential.

## Dataset Information:
- The dataset comprises FIFA21 player information.
- Total dataset size: 17108 entries.
- Number of columns used: 47.

## Exploratory Data Analysis (EDA):
- Initial cleaning involved removing unnecessary columns, handling missing values, and preprocessing currency data.
- Data visualization techniques such as pie charts, bar plots, and scatter plots were employed to understand player attributes and team dynamics.

## Feature Selection:
- Feature selection was performed based on correlation analysis.
- Highly correlated features were removed to avoid redundancy using a threshold of 0.9.
- Features with low correlation to the target variable were dropped to improve model efficiency.

## Modeling:
- XGBoost Classifier was chosen as the predictive model.
- The dataset was split into training and testing sets.
- The model was trained on the training set and evaluated using accuracy and F1 score metrics.
- The trained model achieved high accuracy (99.19%) and F1 score (97.00%), indicating its effectiveness in predicting valuable players in FIFA21.

