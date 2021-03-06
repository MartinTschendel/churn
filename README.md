# churn
Using logictic regression for classification to predict if persons would churn from the services of a telecom company.

This project is taken from "Machine Learning Bookcamp"(Alexey Grigorev)
The dataset is available on: https://www.kaggle.com/blastchar/telco-customer-churn

* The notebook 200820-churn-feature-engineering gives an overall introduction on logistic regression, based on the above mentioned dataset
* The notebook 200822-01-churn-feature-eng calculates the accuracy of the regression model for 3 different scenarios
* as we have a class inbalance within the dataset, it is not enough to just look at the accuracy of the model. The notebook 200903-churn introduces the confusion table as well as the metrics precision and recall
* the notebook 200909-churn further introduces metrics ROC (receiver operating characteristics) curve, what checks the performance of a classifier over different thresholds. Here, the specific focus is put on 2 metrics: TPR (True Positive Rate) and FPR (False Positive Rate)

* 2020-09-14: also the AUC (Area under the ROC curve), k-fold cross-validation and the adjustment of the regularization parameter 'C' are introduced in the notebook 200909-churn now

* 2020-09-17: in the notebook 200914-churn, I analyzed precision and recall for different thresholds. Also plotted a 'precision recall curve'. The goal is that this curve is as closely as possible to the ideal model and as far as possible from the baseline. More information can be found on this [link](https://scikit-learn.org/stable/auto_examples/model_selection/plot_precision_recall.html#:~:text=The%20precision%2Drecall%20curve%20shows,a%20low%20false%20negative%20rate)
