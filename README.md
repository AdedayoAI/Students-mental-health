# Students-mental-health
This is a study showing the possibility of certain factors affecting students mental health thereby leading to depression.

Introduction

This analysis examines the mental health of university students, 
checking to see if a few factors like anxiety, their chosen course of study, gender, 
age etc effect their mental state thereby causing them to be depressed. 
The data set was downloaded from kaggle and a link to the site and dataset has been provided
https://www.kaggle.com/code/shariful07/student-mental-health-data-analysis/data

Two machine learning models will be used to carryout this research;

1: Logistic regression,

2: Random forest,

Importing Some Required Libraries

The major libraries needed for this model are imported in this subsection. Some of which include LogisticRegression, 
a type of statistical analysis used to model the probability of a certain event occurring based on one or more predictor variables. 
It is a binary classification algorithm, meaning it is used to predict the likelihood of an outcome being one of two possible values 
(such as "yes" or "no", "true" or "false", "success" or "failure", etc.).

StandardScaler transforms the data such that the mean of each feature is zero and the variance is one.

Finally, I also downloaded common python libraries for data manipulation such as pandas and numpy.

Model Report
LOGISTIC REGRESSION

The logistic regression model applied to the given dataset achieved an accuracy of 0.7097,
which indicates that 70.97% of the model's predictions were correct. The precision of the model is 0.5833, 
suggesting that when the model predicted a positive result, it was accurate 58.33% of the time.

The recall of the model is 0.6364, meaning that it correctly identified 63.64% of the positive instances in the dataset. 
The f1 score of the model is 0.6087, which provides a measure of the model's overall performance, balancing both precision and recall.

The f1 score of 0.6087 indicates that the model performed reasonably well, but there is room for 
improvement and further analysis and model tuning may be necessary to increase the model's predictive power.

Model Report
RANDOM FOREST
Based on the analysis of the dataset using a random forest model, we achieved an accuracy of 87%, 
indicating that 87% of the predictions made by the model were correct.

The precision score of 95% suggests that among all the positive predictions made by the model, 95% of them were correct.

However, the recall score of 65% implies that the model only identified 65% of all positive samples correctly.

The F1-score of 77% is a harmonic mean of precision and recall, indicating that there is a balance between the two metrics.

Overall, the random forest model performed well in terms of accuracy and precision, but its recall score is relatively low, 
indicating that it may struggle to identify all positive samples in the dataset. 
Therefore, further analysis and optimization of the model may be necessary to improve its performance on this dataset.

Conclusion

In conclusion, the student mental health dataset, with depression as the goal column, 
offers important information about the causes of depression in students. Students' depression 
is significantly predicted by a number of factors, according to the study of the dataset using the random forest model.

The robust machine learning technique known as the random forest model successfully captures the
intricate correlations between the predictor variables and the target variable. High accuracy and
precision ratings for the model show that it is capable of correctly predicting whether or not students 
would experience depression. The model did a good job at identifying students who are at a high risk of 
depression, but its relatively low recall score indicates that it may overlook some occurrences of depression.

Overall, the analysis's findings offer useful data that policymakers and mental health specialists may use to 
create successful interventions and plans for preventing and treating student melancholy. 
Action can be taken to improve students' mental health and wellbeing by addressing the risk factors found in the analysis, 
which will result in higher academic results and a more upbeat attitude on life.




