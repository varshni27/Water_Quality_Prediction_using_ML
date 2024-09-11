# Water Potability Prediction Using Machine Learning

## Project Overview
This project aims to predict the potability of water based on several chemical properties using machine learning classification algorithms. The dataset includes features such as pH, Hardness, Solids, and other water quality indicators to determine whether a water sample is potable (safe to drink) or not. The project demonstrates a full workflow from data preprocessing and exploratory analysis to model building and evaluation.

## Key Features
Exploratory Data Analysis (EDA): Conducted a thorough EDA to understand the distribution and relationships between the features.

- Missing data was handled by replacing null values with median and mean values for features like Sulfate and Trihalomethanes.
- Dropped non-correlating features (pH, Turbidity) to improve model performance.

##Data Preprocessing:

- Scaled feature variables to ensure uniformity in the data using StandardScaler.
- Split the dataset into training and test sets to build robust models.
- Modeling Approach:

## Implemented and compared multiple classification algorithms:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)

Models were evaluated using metrics like **Precision, Recall, F1-Score, and Accuracy** to assess their performance in predicting water potability.

## Technologies Used

**Programming Language:** Python

 **Libraries:**
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Scikit-learn for machine learning models and evaluation

## Results & Insights
- Decision Tree and Random Forest classifiers showed better performance in identifying water potability, with Random Forest being the most balanced model in terms of accuracy and precision.
- Logistic Regression struggled due to the imbalance in classes, highlighting the need for better data balancing techniques in future iterations.

