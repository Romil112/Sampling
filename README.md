# Sampling techniques for making balanced samples from imbalanced dataset
## Introduction
In this assignment we have to apply various sampling techniques to credit catd dataset to make various samples out of it. Then we have to classify various samples correctly using various classification models and compare the accuracy obtained in the form of accuracy matrix. The given dataset contains 772 observations and 31 features. It is a binary classification dataset with 763 0's and only 9 1's. Due to this we need to use effective sampling techniques.

## Balancing the dataset
First we need to balance the ones and zeroes. For that, we can use both oversampling and undersampling. For the above dataset,I have used oversampling whoich resulted in formation of new dataset which has equal zeroes and ones.
## Sampling Techniques
5 Sampling techniques were used on the balanced dataset which are:-

 1.Random Sampling
 
 2.Systematic Sampling
 
 3.Stratified Sampling
 
 4.Convinience Sampling
 
 5.SMOTE(Synthetic Minority Oversampling Technique) with random sampling
 
 ## Model Training

After appling the sampling techniques, the following 5 Machine Learning models are trained on the 5 samples obtained above-

1.Logistic Regression

2.Decision Tree

3.Gradient Boosting Clasifier

4.Naive Bayes Classifier

5.Random Forest Classifier

The accuracy scores of all the models are recorded in a Dataframe which is as follows:

![image](https://user-images.githubusercontent.com/75222834/219958052-edc6d6ac-a08b-4d93-a2c6-4216a53e8a4e.png)


## Conclusion
1.We can determine that for Logistic regression, stratified sampling is giving the best accuracy at 0.940541

2.For Decision Tree, Random sampling is giving best accuracy at 0.989583

3.For Gradient Boosting Classifier, stratified sampling is giving best accuracy at 0.994595

4.For Naive Bayes Classifier, SMOTE is giving best accuracy at 0.844828

5.For Random Forest Classifier,random sampling,systematic sampling and stratified sampling are giving accuracy of 1.0000

Thus the best model is Random Forest.





