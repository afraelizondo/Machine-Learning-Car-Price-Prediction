# Machine Learning project: Car price prediction

## Objectives

- Perform exploratory data analysis to understand the structure and quality of the dataset  
- Preprocess and clean data to handle missing values and feature scaling  
- Build and evaluate multiple regression models for car price prediction  
- Compare model performance in terms of accuracy, F1 score, and training time  
- Identify the most suitable algorithm for the given dataset

## Technologies Used

- **Programming Language:** Python  
- **Data Analysis & Manipulation:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Machine Learning:**  
  - Scikit-learn 
  - XGBoost  
- **Model Evaluation:** Accuracy Score, F1 Score, Mean Squared Error (MSE)  
- **Development Environment:** Jupyter Notebook

## Results 

The following table summarizes the performance of the evaluated models:

<img width="443" height="88" alt="results_comparison" src="https://github.com/user-attachments/assets/3d481ae7-340a-4ae3-b73f-4636656ddaa7" />

Based on the comparative results, K-Nearest Neighbors (KNN) proved to be the most suitable algorithm for this dataset and project objective. KNN achieved the same accuracy and F1 score as Random Forest while requiring significantly less training time, making it the most efficient option given the dataset size. In addition, its simplicity and intuitive behavior make it an effective and interpretable baseline model for car price prediction, offering a strong balance between performance, efficiency, and clarity.

## Next Steps

- Perform hyperparameter tuning to further optimize model performance  
- Explore feature engineering and feature selection techniques  
- Evaluate additional regression models  
- Assess model performance using cross-validation





