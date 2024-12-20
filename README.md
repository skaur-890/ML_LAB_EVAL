# ML-LAB-EVAL
 This work is submitted for the lab evaluation of the Machine Learning (UML501) course. This project aims to predict the performance of a fuel cell using machine learning techniques.
 
## Methodology

1. Data Loading and Preprocessing:  
     ○ The dataset is loaded using Pandas.  
     ○ Columns ('Target1', 'Target2', 'Target4', 'Target5') are dropped according to 
       instructions.  
     ○ PyCaret's setup function is used for preprocessing, including:  
               > -Data splitting (70% train, 30% test)  
               >> -Normalization (Robust scaler)  
               >> -Transformation (Yeo-Johnson)  
               >> -PCA (Incremental)  
               >> -Outlier removal (5% threshold)  

2. Model Comparison and Selection:  
    ○ PyCaret's compare_models function is used to evaluate various regression models.

3. Model Training and Evaluation:  
    ○ Each selected model is trained using PyCaret's create_model function.  
    ○ Predictions are made on the entire dataset using predict_model.  

4. Results and Metrics:  
    ○ Performance metrics (R2, MAE, MSE,RMSE,MAPE) are collected for each model.  
   
## Detailed Result Analysis:  

![image](https://github.com/user-attachments/assets/e5df5628-e0a5-447b-8e46-30d4dc6af631)


# Results:  
The best-performing model is Linear Regression with an R-squared value of 0.2540







