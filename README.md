# Comparative-study-of-various-Classification-Algorithms-in-Machine-Learning

## ABOUT THE PROJECT
* We all experience anxiety; it is a natural human state and a vital part of our lives. Anxiety is often regarded as an artefact of modern societies, one that is increasingly represented in visual arts, music, literature, and social media. Anxiety helps us to identify and respond to danger in ‘fight or flight’ mode. It can motivate to us face up to dealing with difficult challenges. The ‘right’ amount of anxiety can help us perform better and stimulate action and creativity. But there is another side to anxiety. Persistent anxiety causes real emotional distress and can lead to us becoming unwell and, at worst, developing anxiety disorders such as panic attacks, phobias and obsessional behaviours. Anxiety at this level can have a truly distressing and debilitating impact on our lives and impact on our physical as well as our mental health.
* Machine learning, a fast-growing approach that’s spreading out and helping every sector in making viable decisions to create the foremost of its applications. Our main objective is to classify and find out the levels of anxiety among different age groups. 
* Various Machine Learning algorithms were applied to predict the level of anxiety. GridSearchCV, a tuning technique was applied compute the optimum values of hyperparameters. Amongst all, Voting Classifier works the best with 96.95% accuracy followed by Gradient Boosting with Support Vector Classifier as the base estimator with 96.67% accuracy.

## ACCURACY AND AUC SCORE TABLES
* Here is a tabular representation of the accuracy on test set, K-fold accuracy and the AUC score which is also obtained using K-fold Cross validation for our various classification models. For the K-fold accuracy and AUC score the value of K we took was 10.
* The choice of k is usually 5 or 10, but there is no formal rule. As k gets larger, the difference in size between the training set and the resampling subsets gets smaller. As this difference decreases, the bias of the technique becomes smaller.
* There is a bias-variance trade-off associated with the choice of k in k-fold cross-validation. Typically, given these considerations, one performs k-fold cross-validation using k = 5 or k = 10, as these values yield test error rate estimates that suffer neither from excessively high bias nor from very high variance.

<p align="center">
  <img src="https://user-images.githubusercontent.com/71218441/154526157-4c8e3bc3-0d1f-44fb-ae2d-b20bb82981a5.png" width="550" height="250"/>
  <img src="https://user-images.githubusercontent.com/71218441/154526186-1115c6b2-25d0-46eb-bc54-43c9de7110cf.png" width="650" height="350"/>
  <img src="https://user-images.githubusercontent.com/71218441/154526224-36037ddc-6a8f-4275-af5b-faabd424a410.png" width="450" height="180"/>
</p>

## CONCLUSION
* Various machine learning algorithms were applied to determine four different severity levels of anxiety. Data was collected using a standard questionnaire i.e., TMAS. Subsequently six different classification techniques were applied – namely Naïve Bayes, KNN, Logistic Regression, Support Vector Machine, Decision Tree, Random Forest Tree. Also, GridSearchCV, K-fold cross validation, two techniques of boosting – Adaboost and Gradient Boosting and Voting Classifier were applied. Amongst all, Voting Classifier works the best with 96.95% accuracy followed by Gradient Boosting with Support Vector Classifier as the base estimator with 96.67% accuracy. The important variable found were: 
* Q3. I believe I am no more nervous than most others.
* Q24. I dream frequently about things that are best kept to myself.
* Q30. I cry easily.
* Q11. I worry quite a bit over possible misfortune.<br>
As such these variables were considered most important in detecting anxiety.
