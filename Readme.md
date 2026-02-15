NutriClass: Food Classification Using Nutritional Data

Project Overview

NutriClass is a machine learning project that classifies food items based on their nutritional attributes such as calories, protein, carbohydrates, fat, sugar, fiber, sodium, cholesterol, glycemic index, water content, and serving size. The model predicts the exact food name using these nutritional features.

This project focuses on building a multi-class classification system that can accurately identify food categories and support strict diet planning applications.

Problem Statement

In today’s health-conscious environment, classifying food based on nutritional values is important for maintaining dietary balance. This project develops a machine learning model that predicts the food name from nutritional metrics. Unlike recommendation systems that provide multiple options, this system predicts one exact food item, making it suitable for strict diet and meal planning scenarios.

Business Use Cases

This system can be used in smart diet applications to classify food automatically based on nutritional input. It can assist nutritionists in planning meals and tracking dietary intake. Food logging applications can use this model to categorize user food entries. Educational platforms can use it to help students understand nutrition and food classification. It can also be integrated into grocery and meal planning applications for better food selection.

Approach

Data Understanding and Exploration

The dataset was loaded and examined to understand its structure, size, and class distribution. Sample records were viewed to understand variation between food categories. Missing values and duplicate entries were checked.

Data Preprocessing

Missing values were handled appropriately. Duplicate rows were removed. Numerical features were standardized using StandardScaler. The dataset was split into training and testing sets to evaluate model performance.

Feature Engineering

Principal Component Analysis was applied to reduce dimensionality while retaining 95 percent of the variance. This helped in understanding how much information is captured by fewer components and ensured efficient model training.

Model Selection and Training

Multiple machine learning models were trained and compared:

Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors
Support Vector Machine
Gradient Boosting Classifier

Model Evaluation

Each model was evaluated using accuracy, precision, recall, F1-score, and confusion matrix. Five-fold cross-validation was performed to ensure model stability and generalization.

Results

The Support Vector Machine achieved the highest accuracy of 99.35 percent. The mean cross-validation accuracy was 99.27 percent, indicating strong and stable performance. Other models such as Random Forest and Gradient Boosting also performed competitively.

The confusion matrix showed very minimal misclassification, indicating clear separation between food categories.

Real-Time Applicability

This system can be integrated into real-time diet planning applications. A user can provide nutritional requirements such as high protein or low fat, and the system will predict the exact food name that matches those requirements. This ensures strict diet adherence and personalized meal selection.

Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook

Conclusion

This project successfully developed a robust multi-class classification model to predict food names based on nutritional attributes. The final model demonstrates high accuracy and strong generalization capability. The system can be applied in health monitoring tools, diet planning applications, and automated food logging systems.

Author

Gomathi Boopathy
Machine Learning Project
Domain: Food and Nutrition