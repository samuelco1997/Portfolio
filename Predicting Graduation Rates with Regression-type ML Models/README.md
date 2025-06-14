# Predicting Graduation Rates with Regression-type ML Models

For this personal portfolio project, I aimed to create an algorithm that could predict the 4-year graduation rate of higher education institutions using various performance metrics. The data set (“IPEDS_data”) comes from Kaggle (link below), and contains data on school composition, enrollment and graduation rates, demographics, test scores, and more. Raw and cleaned data can be found in the "Data" folder. The target feature in this case is “Graduation rate - Bachelor degree within 4 years, total.” I employed three ML models: Regression trees, LASSO regressions, and XGBoost. Preliminary models were then hyperparameter tuned for optimization. A hyperparameter tuned XGBoost model showed the highest performance (MAE = 4.21, RMSE = 5.70).

### Code
The three Python notebooks here can be downloaded and should be run in the following order:

1)	**EDA_IPEDS**: Exploratory data analysis on raw data.
2)	**Preprocessing_IPEDS**: Readying data for model use, including cleaning, imputing, one-hot encoding.
3)	**Model Evaluation_IPEDS**: Fitting models to the data, hyperparameter tuning, and goodness-of-fit evaluations.

If downloaded directly, no change in directory is needed (there are relative paths). More information on IPEDS can be found at the National Center for Education Statistics website below. 

### Data
Data can be found in the "Data" folder. The IPEDS dataset used here is from Kaggle, and details performance, enrollment, and graduation data of different universities throughout the United States.

### Sources
Kaggle Data Set - https://www.kaggle.com/datasets/sumithbhongale/american-university-data-ipeds-dataset 

NCES IPEDS Information - https://nces.ed.gov/ipeds 
