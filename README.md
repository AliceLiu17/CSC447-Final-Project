# Wine Quality Prediction

![](https://github.com/AliceLiu17/Wine-Quality-Prediction/blob/main/readme%20image.png)


### Models Used
- Logistic Regression (max_iter = 1000)
- Logistic Regression 
- Decision Tree
- Decision Tree (criterion = gini)
- Random Forest (n_estimators = 200)
- Random Forest
- Gradient Boosting
- K-Neighbors (n_neighbors = 5)
- K-Neighbors (n_neighbors = 10)
- Extra Trees (n_estimators = 200)
- SGD Classifier (loss = hinge)
- SGD Classifier (loss = modified_huber)
- SGD Classifier

----

### Feature Selection

After several experimentation, the features that yielded the best accuracy result was: 
1. 'alcohol'
2. 'sulphates'
3. 'volatile acidity'

**Note: These features were Top 3 features from Feature Importance using Random Forest** 

----

### Results

| Model    | Accuracy Score |
|---------|-----|
| Logistic Regression (max_iter = 1000)  | 57.5%  |
| Logistic Regression    | 57.5%  |
| Decision Tree   | 66.1% |
| Decision Tree (criterion = gini)    | 66.1%  |
| Random Forest (n_estimators = 200)    | 72.4% |
| Random Forest    | 71.7%  |
| Gradient Boosting    | 67.7%  |
| K-Neighbors (n_neighbors = 5)    | 52.8% |
| K-Neighbors (n_neighbors = 10)    | 57.5%  |
| Extra Trees (n_estimators = 200)    | 74.0%  |
| SGD Classifier (loss = hinge)    | 41.7%  |
| SGD Classifier (loss = modified_huber)    | 41.7%  |
| SGD Classifier   | 41.7%  |
