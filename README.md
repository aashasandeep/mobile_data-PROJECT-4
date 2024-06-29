# mobile_data-PROJECT-4
# Feature Extraction and Price Prediction for Mobile Phones

## Project Overview
This project aims to predict the prices of mobile phones based on their specifications using machine learning models. By understanding the key factors that influence mobile phone prices, we can provide valuable insights for consumers, manufacturers, and retailers.

## Objectives
- To load and explore the mobile phone dataset.
- To preprocess the data by handling missing values, outliers, and inconsistencies.
- To extract and analyze features that strongly affect mobile phone prices.
- To build and evaluate multiple machine learning models for price prediction.
- To generate insights and provide recommendations based on the analysis.

## Dataset
The dataset contains information on various mobile phones, including their specifications and prices. The key features include:
- Model
-  memory
- Color
- Screen Size
- Battery Capacity
- RAM
- Storage
- presence of AI lens
- rear camera specifications
- Front Camera Specifications
- mobile height
- Price

## Steps Involved
### 1. Data Exploration
- Load the dataset and explore its structure.
- Understand the data types and the range of values for each feature.

### 2. Data Preprocessing
- Handle missing values, outliers, and inconsistencies in the dataset.
- Convert categorical variables (e.g., model, color) into numerical formats using one-hot encoding.

### 3. Feature Extraction
- Identify and extract relevant features using statistical methods and visualizations.
- Perform feature importance analysis to select the most impactful features.

### 4. Model Building
- Split the dataset into training and testing sets.
- Develop machine learning models such as linear regression, decision trees, random forests, and gradient boosting.

### 5. Model Evaluation
- Evaluate the models' performance using metrics like mean absolute error and root mean squared error.
- Analyze feature importances to confirm the significance of extracted features.

### 6. Insights and Recommendations
- Generate insights from the analysis and model results.
- Provide actionable recommendations for stakeholders based on the findings.

## Conclusion
This project demonstrates the process of building a predictive model for mobile phone prices, from data exploration and preprocessing to feature extraction and model evaluation. The insights gained can help inform better decision-making in the mobile phone market.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Load the dataset and follow the steps outlined in the notebook to perform the analysis and model building.
