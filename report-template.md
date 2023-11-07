# Module 12 Report Template

## Overview of the Analysis


* Explain the purpose of the analysis.

The purpose is to to evaluate and determine the accuracy of a data model

loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt	loan_status
0	10700.0	7.672	52800	0.431818	5	1	22800	0
1	8400.0	6.692	43600	0.311927	3	0	13600	0
2	9000.0	6.963	46100	0.349241	3	0	16100	0
3	10700.0	7.664	52700	0.430740	5	1	22700	0
4	10800.0	7.698	53000	0.433962	5	1	23000	0


loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt
0	10700.0	7.672	52800	0.431818	5	1	22800
1	8400.0	6.692	43600	0.311927	3	0	13600
2	9000.0	6.963	46100	0.349241	3	0	16100
3	10700.0	7.664	52700	0.430740	5	1	22700
4	10800.0	7.698	53000	0.433962	5	1	23000



## Results

* Machine Learning Model 1:
Model 1 Accuracy: 0.952.
Model 1 Precision: for healthy loans the precision is 1.00, for high-risk loans the precision is 0.85.
Model 1 Recall: for healthy loans the recall score is 0.99, for high-risk loans the recall score is 0.91


* Machine Learning Model 2:
Model 2 Accuracy: 0.995.
Model 2 Precision: for healthy loans the precision is 0.99, for high-risk loans the precision is 0.99.
Model 2 Recall: for healthy loans the recall score is 0.99, for high-risk loans the recall score is 0.99.

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Second model performs best. The high risk loans are better and more important to predict

