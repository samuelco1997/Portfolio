For this personal portfolio project, I aimed to create machine learning algorithms that could predict the 4-year graduation rate of higher education institutions. The data set (“IPEDS”) comes from Kaggle (here), and contains data on school composition, enrollment and graduation rates, demographics, test scores, and more. The target feature in this case is “Graduation rate - Bachelor degree within 4 years, total.” I employed three ML models: Regression trees, LASSO regressions, and XGBoost. Preliminary models were then hyperparameter tuned for optimization. 
The three Python notebooks here can be downloaded and should be run in the following order:

1)	**EDA_IPEDS**: Exploratory data analysis on raw data.
2)	**Preprocessing_IPEDS**: Readying data for model use, including cleaning, imputing, one-hot encoding.
3)	**Model Evaluation_IPEDS**: Fitting models to the data, hyperparameter tuning, and goodness-of-fit evaluations.

If downloaded directly, no change in directory is needed (there are relative paths). More information on IPEDS can be found here, at the National Center for Education Statistics. 
