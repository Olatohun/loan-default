# Title: Loan Default Predictions

1.	Project Motivation
2.	Installation
3.	Data
4.	Implementation
5.	Results


### Project Motivation
The aim of this project is to predict whether loan applicants have the tendency to default the loan or not. 

### Installation
Python V-3.

**Libraries:**
-	Scikit Learn
-	Imblearn. 
-	Pandas. 
-	Numpy.
-	Seaborn
-	Matplotlib.


### Data
The data was gotten from the summer training hackathon [Analytics Vidya](https://datahack.analyticsvidhya.com/contest/machine-learning-summer-training-hackathon/#LeaderBoard). The hackathon concluded on 31-07-2022. 


### Implementation
Various classification models were used in search of the model with the highest macro F1 score. The target variable had only on value. Which prompted predicting the target variable again and joining it with the original dataset. The variable was then balanced using SMOTE from the Imblearn library. 

Details about the models’ performance on the different sets of data is available in the notebook. 

The models were run on selected features data with a ratio of 60:40 and the performance of the model was reviewed using the classification_report metric to display a summary of accuracy score, precision score, recall score and f1_score as shown in the notebook


### Results
The output of the prediction result is in the ‘ld_predictions.csv’ above and in the notebook as well
