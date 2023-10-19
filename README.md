# Taiwan Clients Default of Credit Card (classification)

This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods, However in this self hands on project I only applied 2 alogrithms (SVM and Boosting machines).

![image](https://github.com/Kmohamedalie/Taiwan-Clients-Default-of-Credit-Card/assets/63104472/7e6323ed-6f8e-4446-ac28-d70342bf17ca)


<br> 

**Dataset:** <a href="https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients">UCI Machine Learning</a>,   <a href="https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset">Kaggle</a>


**Complete JupyterNotebook:** [Link](https://github.com/Kmohamedalie/Taiwan-Clients-Default-of-Credit-Card/blob/master/Notebook/TaiwanClients%20Default%20of%20Credit%20Card%20-%20SnapML(Random%20Forest%20vs%20Boosting%20Machine)%20.ipynb)


**Metrics Achieved:**  
| Algorithm |Accuracy | f1-score |
| --------- | -----------| ------- |
| Boosting Machines | 82% |79.32% |


<br>

**Additional Information about the dataset**

This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel Sorting Smoothing Methods to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. Therefore, among the six data mining techniques, artificial neural network is the only one that can accurately estimate the real probability of default.
