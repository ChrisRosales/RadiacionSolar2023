# Efficient Machine Learning Models for Solar Radiation Prediction Using Ensemble Techniques

This report explores the development of machine learning models tailored to predict solar radiation in regions with unique climatic conditions, such as Lima, Peru, characterized by arid and low-rainfall environments. The study incorporates data preprocessing, dimensionality reduction through PCA, and the evaluation of various regression algorithms, including:

- Polynomial Regression
- Decision Trees
- Random Forest
- Artificial Neural Networks
- KNN
- Gradient Boosting

To enhance predictive accuracy, the report delves into **ensemble learning techniques**, such as Voting, Stacking, and Bagging. Among these, the **Stacking Regressor**, combining Random Forest, Decision Tree, Gradient Boosting, and KNN, achieved the best metrics, demonstrating robustness and high accuracy (\( R^2 = 0.92\)).

## Key Components:
- **Data Processing**: Utilization of meteorological variables collected from a weather station to create a clean dataset spanning 2023. Dimensionality reduction was applied using **Principal Component Analysis (PCA)** to enhance computational efficiency and reduce noise in the dataset while preserving the most significant patterns.
- **Machine Learning Models**: Detailed evaluation of individual ML models and their performance metrics.
- **Ensemble Learning**: Implementation and comparison of ensemble models, highlighting improvements in generalization and predictive accuracy.
- **Visualization and Results**: Graphical representations of model performance and validation across datasets.
- **Discussion**: Analysis of the models’ applicability to similar climates and the trade-offs between computational cost and accuracy.

This work demonstrates the potential of advanced ML and ensemble methods in optimizing solar radiation predictions, especially in underrepresented regions with limited access to measurement tools.
