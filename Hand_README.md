# Hand Predictions Modes

## In this taks, we received a training datas that contains a hand mode between 2 persons:
 *Spontaneous- when both of the pepole moving their hands freely.
 
 *Syncronaize- when they moving their hands together .
 
 *Alone- when only one of them is moving their hand.
 
 The goal of the task is to identify which one of the training data sets is the hand mode that he has.
 By training the files and combining them to one big data base that contains all of the hand movement.
 We can predict the result by taking all the important numeric features from the data and evaluate the best model to use.
 
 By combining the training files and combined 5 rows into 1 row at all, we got more accurate results.
 Then we checked the results according to the validation files of the task:
 
 | Model        | Validation      | 
| ------------- |:-------------:| 
| Logistic Regression      | 78% | 
| Naive Bayes      | 74% | 
| KNN      | 95% | 
| Random Forest      | 79% | 
| Decision Tree      | 93% | 
 
 
 
 
 
