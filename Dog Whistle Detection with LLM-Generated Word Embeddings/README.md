# Dog Whistle Detections with LLM-Generated Word Embeddings

For this project in my Neural Networks class, I attempted to create a dog whistle classification system using LLM-generated word embeddings from the DistilBERT transformer in combination with traditional supervised learning techniques, namely K-Nearest Neighbor and Logistic Regression. Results were compared with simple Word2Vec embeddings. Results were promising, with accuracy and F1 scores above 0.90.

### Code
This folder contains all of the files and data necessary to carry out this process. The code should be run in the following order:

**1) DW_EDA_&_Cleaning**  - *Exploratory Analysis and Data Cleaning*

**2) DW_Modeling** - *Training the models*

### Data
Please note that there are two raw data sets being used: reddit comments containing dog whistles (**"silent_signals_dw"**), and reddit comments that do not (**"reddit_question_best_answers"**). Because the latter was to large to upload to this repository, I have provided a link in the folder (**"RS_2013-12.jsonl"**)

### Analysis
A report and slide deck detailing my findings and motivations for this project can be found in the **Analysis** folder.
