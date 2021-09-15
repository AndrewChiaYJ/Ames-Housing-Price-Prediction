# Codes Sequence

### **Do read the codes in the order below, so as to understand better on the codes and thought process.**


**1) Part 1 - Train.csv - P. Statement, Background, Cleaning & Dummifying**


This code is to state the problem statement and background of the project. 


Followed by processes done to clean the train.csv data, as well as to dummify the variables for the modelling to be done in a later stage.



**2) Part 2 - Train.csv - EDA, Data Visualization, Modelling, Model Evaluation & Fitting, and Conclusion**


This code is to do EDA and data visualization on the cleaned and dummified dataset. 


Followed by modelling process (Linear regression model, Ridge Model, Lasso Model, Baseline RMSE calculation.


Then model evaluation is done and Ridge Model is chosen to be the best model. 


Some data visualization is done to observe insights on the coefficient of the Ridge model. 


Following by using the Ridge Model to predict the values of y using test.csv (Here use the test_modified_dummified.csv, which is cleaned, and dummified in Appendix 1 - Test.csv - Cleaning and Dummifying)


After predicting the values of y, saved in a new test_kaggle.csv in Kaggle Submission folder, then submit to Kaggle for evaluation.


Lastly, conclusions and future works of this project.

**3) Appendix 1 - Test.csv - Cleaning and Dummifying**


This code is to clean the test.csv data, as well as to dummify the variables for the modelling prediction to be done in late of Part 2 codes.


**4) Appendix 2 - Data Dictionary**


This code is the data dictionary for all the variables in datasets used for better understanding of what the items in datasets mean.