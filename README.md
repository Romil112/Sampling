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

![image](https://user-images.githubusercontent.com/75222834/219948510-681dcafa-3a7c-497a-9500-9c8492b18f15.png)

## Conclusion
1.We can determine that for Logistic regression, stratified sampling,convinience sampling and SMOTE are giving best accuracy of 0.940541

2.For Decision Tree, Random sampling is giving best accuracy at 0.989583

3.For Gradient Boosting Classifier, stratified sampling,convinience sampling and SMOTE are giving best accuracy of 0.994595

4.For Naive Bayes Classifier, Systematic Sampling is giving best accuracy at 0.83333

5.For Random Forest Classifier,every model is giving accuracy of 1.0000






