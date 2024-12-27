# Wine-Quality-Prediction

This project aims to predict the quality of wine based on various physicochemical features using machine learning algorithms. The dataset contains information about different chemical properties of wine such as acidity, alcohol content, and sulfur levels, along with the wine's quality rating.


**Project Overview**

Wine quality is a subjective measure influenced by various factors including the chemical composition of the wine. In this project, we analyze a dataset containing multiple physicochemical features of wine and use this data to predict whether a wine is of good quality or bad quality. This classification problem is tackled using various machine learning models.


**Objectives**

  Predict Wine Quality: Classify wines into two categories - "Good" (quality >= 6) and "Bad" (quality < 6).
  
  Data Exploration: Analyze how different features such as acidity, alcohol, sulphates, etc., influence the quality of wine.
  
  Data Preprocessing: Clean the dataset by handling missing values, detecting outliers, and scaling the features.
  
  Model Building: Train several machine learning models to predict wine quality.
  
  Model Evaluation: Evaluate the performance of each model using accuracy, classification report, confusion matrix, and ROC curves.


**Dataset**

The dataset used in this project includes the following columns:

  fixed acidity
  volatile acidity
  citric acid
  residual sugar
  chlorides
  free sulfur dioxide
  total sulfur dioxide
  density
  pH
  sulphates
  alcohol
  quality (Target variable)
  
The target variable quality represents the quality rating of wine, ranging from 0 to 10, where 0 is the worst and 10 is the best.


**Steps Involved**

**1. Data Preprocessing**

**Loading and Checking the Data:** The dataset is loaded and checked for missing values, and outliers.
**Feature Scaling:** We use standard scaling to normalize the features for better model performance.
**Balancing the Data:** The dataset is balanced to avoid biased model predictions for classes with higher counts.
**Handling Outliers: **Outliers are detected and removed to improve model accuracy.


**2. Data Visualization**

**Various visualizations are created to explore the relationships between the features and the target variable. These include:**

  Histograms to visualize the distribution of the quality of wine.
  Correlation Heatmaps to understand relationships between features.
  Box Plots to explore the distribution of acid levels in good and bad wines.
  Pair Plots to visualize interactions between key features like acidity and alcohol.

**3. Machine Learning Models**

**Different machine learning models are trained to predict wine quality:**

  Logistic Regression
  Support Vector Classifier (SVC)
  Decision Tree Classifier
  Random Forest Classifier
  Gradient Boosting Classifier
  K-Nearest Neighbors (KNN) Classifier

Each model is evaluated using performance metrics such as accuracy, confusion matrix, and ROC curve.


**4. Model Evaluation**

**For each model, the following metrics are used to evaluate performance:**

 ** Confusion Matrix:** To show true positives, true negatives, false positives, and false negatives.
 ** Classification Report:** To display precision, recall, and F1-score.
 ** ROC Curve:** To visualize the model's ability to distinguish between good and bad wines.
 

**Key Visualizations**

  **Distribution of Wine Quality:** A histogram to show how wine quality is distributed across the dataset.
  
  ** Boxplots and Violin Plots:** To visualize the relationship between acidity and wine quality.
  
  **Scatter Plots:** To show the relationship between alcohol content, acidity, and quality.
  
  **Correlation Heatmap:** To analyze how different features correlate with each other and with the quality of the wine.
  

**Results**

**Accuracy:** The performance of each machine learning model is compared based on accuracy scores.

**Best Model:** The best-performing model is selected based on the evaluation metrics, such as accuracy and F1-score.

