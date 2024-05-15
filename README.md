# Predicting Myocardial Infarction Outcomes

Can outcomes (death, various medical complications) be predicted for patients who end up in the ER for myocardial infarctions? Knowing early on (i.e. at the time of admission) which patients are more at risk could lead to their care being prioritized. 

Logistic regression and XGBoost were used to classify survival for ER patients with myocardial infarctions. They both performed well, with an area under the ROC curve of 0.9081 and 0.8472 respectively. The accuracy and precision were very similar for both models. The most predictive feature in each model was different. When attempting to classify other outcomes, the logistic regression had good accuracy but poor precision and mediocre AUC which is likely due to an imbalance in the class divisions. The accuracy is likely misleadingly high. It would be worth looking into methods to deal with this.
