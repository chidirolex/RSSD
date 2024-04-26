# RSSD
RSSD Final Data Scientist Challenge


Insurance Charges Prediction Project

Summary:

The project aims to predict medical insurance charges based on various demographic and lifestyle factors using machine learning techniques. The dataset contains information such as age, sex, BMI, number of children, smoker status, region, and charges.

Exploratory Data Analysis (EDA):

Initial Data Analysis: Provided an overview of the dataset's structure and contents.
Summary Statistics: Presented summary statistics for the charges variable.
Regional Distribution: Tabulated and visualized the number of people in each region using a bar plot.
Scatterplot Matrix: Created a scatterplot matrix to visualize the relationships among all features.


Model Training and Evaluation:
Data Preprocessing: Converted categorical variables into numerical format using one-hot encoding.
Model Splitting: Split the data into training and testing sets.
Linear Regression: Trained a linear regression model on the data and evaluated its performance using R-squared score. The model achieved a train R^2 score of approximately 74.2% and a test R^2 score of approximately 77.0%.
Model Improvement: Explored model improvement techniques by adding polynomial features and interaction features. While polynomial features led to decreased performance, the inclusion of an interaction feature between smoker status and obesity (BMI > 30) significantly improved model performance, with train and test R^2 scores of approximately 86.0% and 88.0%, respectively.
Additional Insights:

Visualizations: Explored relationships between variables through various visualizations, including the number of smokers by region, smokers by sex, and BMI categories by sex.
BMI Impact: Examined the impact of BMI on smoker status, revealing a higher proportion of smokers among individuals with BMI > 30.
BMI Distribution: Visualized the distribution of BMI categories by sex, highlighting a higher proportion of males with BMI > 30.
Conclusion:

The project demonstrates the importance of considering interaction effects and non-linear relationships to improve model performance in predicting insurance charges. Additionally, insights from visualizations provide valuable information about the relationships between different demographic and lifestyle factors in the dataset.
