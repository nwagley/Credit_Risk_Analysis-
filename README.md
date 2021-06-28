# Credit_Risk_Analysis-


## Introduction 
For this project we will be employing different techniques to train and evaluate models with unbalanced classes. Jill asked us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

We will be oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We will then use a combinatorial approach of over and undersampling using the SMOTEENN algorithm. Finally we will be compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

Below are some of the results achived in the test. 

## Results 

<img width="801" alt="1" src="https://user-images.githubusercontent.com/79885849/123572958-4a7b8600-d78a-11eb-8faa-91428d2fb945.PNG">

<img width="729" alt="4" src="https://user-images.githubusercontent.com/79885849/123572959-4a7b8600-d78a-11eb-9e28-0caedb74da3f.PNG">

 

In the above tables, we can see that the accuracy score for all over and undersampling methods had bad scoresscores ranging from the low 50 percents to the high 60 percents. using the ensable clasifiers improved the accuracy score to the high 80 percents or the low 90 percents. 

<img width="804" alt="b1" src="https://user-images.githubusercontent.com/79885849/123573007-5ebf8300-d78a-11eb-853b-107f6033a740.PNG">
<img width="806" alt="b2" src="https://user-images.githubusercontent.com/79885849/123573012-5f581980-d78a-11eb-98a3-b4f1de576fb5.PNG">
<img width="735" alt="b6" src="https://user-images.githubusercontent.com/79885849/123573014-5ff0b000-d78a-11eb-8f69-509f5e3155eb.PNG">


However, the precision of the both ensamble models remained poor leading on overall low F1 score for both.

## Summary
 At the end we can say that a lot of customers are being turned down because they are being tagged as high risk even when they are not which means ultimately the bank is missing out on good customers which will help them make profit. I would not recomment to use any of the above 6 models.These methods seen above are better at predicting high risk loans with accuracy in the high 80s to low 90s.Whereas with a low numbers for both models, we see a lot of high number of false positives.
