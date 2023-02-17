# KP_Supervised_ML_Challenge

 ## Challenge
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

**My Prediction**
I think the Random Forest Classifier model will be the most effective with this data. Since the lending company is looking to asses risk factors of loans, the model needs to examine a wide range of features to create a classification of risk level behaviors. The logistic regression model is looking for a binary outcome from the data not a level of risk.  

**Model Reports**

*Logistic Regression*

- Training Data Score: 0.9942908240473243
- Testing Data Score: 0.9936545604622369

![image](https://user-images.githubusercontent.com/110507463/219741352-7c02332e-ba34-4795-8258-d1f1470d3f07.png)

*Random Forest Classificaiton*

- Training Score: 0.9974893382858715
- Testing Score: 0.9910751134956666

![image](https://user-images.githubusercontent.com/110507463/219741546-9f1eadce-d430-4778-835a-dfcdf2cfeb7e.png)


**My Conclusion**
For both models, the trainging and test scores are very close so the models are not over-fitting. Both models also score 99% the same for precision, the logistic regression scores better in recall, and the logistic regression also has a better F1 score. Based on these results, the Logistic Regression model is the better model for this data. Thus, my prediction was incorrect. 
