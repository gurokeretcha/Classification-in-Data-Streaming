# Project on Classification in Data Streams


## Objective:
The goal of this lab is to build a classifier capable of learning and making predictions in a datastream using the River library. In this lab we are comparing three datastream classifiers on Electricity dataset

- kNN
- Hoeffding Tree
- Batch-Incremental Ensemble Classifier (BIE)

batchClassifier waits 100 sample models, than train the model, adds another 100 points and trains the model again untill 100 max models and after the olders model is removed

## Results
![alt text](https://github.com/gurokeretcha/Classification-in-Data-Streaming/blob/main/result_img/result.png)

As you can see, the result of three data stream classifiers are prety decent, however the computation time is different.
 



