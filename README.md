# Machine-Learning-Project
Laptop Price Prediction and Classification
This repository features a machine learning project focused on analyzing laptop prices and predicting laptop types based on various specifications. Utilizing a dataset that includes information on different laptop models, the project aims to provide valuable insights into the factors influencing laptop prices.

Project Overview
The project includes several key components:

Data Cleaning and Preparation: The dataset is carefully cleaned and preprocessed to handle missing values and ensure all relevant features are in the correct format. This step is crucial for accurate analysis.

Exploratory Data Analysis (EDA): Comprehensive EDA is conducted to uncover patterns and relationships within the data. This includes identifying the top laptop brands, calculating average prices by brand, and visualizing correlations between numeric features. Various plots, such as heatmaps and distribution graphs, are employed to illustrate findings.

Feature Engineering: New features are created, such as StorageTotal, which sums primary and secondary storage capacities, enhancing the model's predictive capabilities.

Model Development: Two primary machine learning models are built:

Regression Model: A linear regression model predicts laptop prices using features like RAM, screen size, CPU frequency, and GPU brand. The performance is evaluated using metrics such as R² and Mean Squared Error (MSE).
Classification Model: A random forest classifier categorizes laptops based on features like screen size, RAM, and weight. The model's accuracy, confusion matrix, and classification report provide insights into its effectiveness.
Results and Evaluation: The project concludes with a comparison of model performances, offering recommendations for the best regression and classification models based on evaluation metrics.

This repository serves as a practical guide for anyone interested in machine learning applications in market analysis, providing a framework for understanding laptop pricing dynamics.
