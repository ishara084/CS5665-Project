# CS5665 - Final Project

## Folder structure
```
|-- root
    |-- submission                                    ------------> Kaggle Submission files (Not included due to the large size)
    |-- data                                          ------------> Original data (Not included due to the large size)
    |-- 1. simple_linear_regression.ipynb             ------------> Linear regression - Least Squre method
    |-- 1.1 simple_linear_regression_with_gd.ipynb    ------------> Linear regression - Gradient Descent
    |-- 2. polynomial_linear_regression.ipynb         ------------> Polynomial regression model 
    |-- 3. XGBRegressor.ipynb                         ------------> XGBRegressor model 
    |-- 4. LightGBM.ipynb                             ------------> LightGBM model 
    |-- 5. RF_Regressor.ipynb                         ------------> RF_Regressor model (Not included in the report due to longer execution time)
    |-- 6. LSTM_base.ipynb                            ------------> Base LSTM model
    |-- 7. BiLSTM_base.ipynb                          ------------> Base Bi-LSTM model
    |-- 7. BiLSTM_neurons_sensitivity.ipynb           ------------> Sensitivity analysis for Bi-LSTM Model
    |-- 7. BiLSTM_final.ipynb                         ------------> Final Bi-LSTM Model
```

## Read this
  - Each model has a separate notebook with annotations and comments. This is for clarity and to tweak the model architectures if needed.


##  Steps to execute
- Install necessary libraries before executing the notebook files
  - ```pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124``` (I used CUDA for GPU performance utilization, but the code works without it, just taking a longer time)
  - ```pip install -U scikit-learn```
  - ```pip install pandas```
  - ```pip install matplotlib```

Source of the Images & Access Conditions
- Dataset used: [https://www.kaggle.com/competitions/internal-waves/data](https://www.kaggle.com/competitions/ventilator-pressure-prediction/data)
