# Feature_Extraction
## Data Set
1- Wine Data https://archive.ics.uci.edu/ml/datasets/wine
2-Car Evaluation https://archive.ics.uci.edu/ml/datasets/car+evaluation

## ML Techniques 
LogisticRegression, GuassianNB,ExtraTreesClassifier(Feature Importance)

Decision boundary with 2 features using LogisticRegression,GuassianNB
![image](https://user-images.githubusercontent.com/109751694/209457323-7e81f756-6397-4b35-9f1a-3a86d2914a92.png)
### Splitting Data into train test valid. (Car Evaluation)

## KneighborsClassifier with Car Evaluation data set
![image](https://user-images.githubusercontent.com/109751694/209457340-b8cfa248-06a6-4685-9ab0-2922b93a3d42.png)
### Accuracy Curves [Validation].
![image](https://user-images.githubusercontent.com/109751694/209457345-3df58be7-60b8-4d05-b589-d7b394a764c4.png)
## Bar Chart showing the Prediction time across the 4 cases

![image](https://user-images.githubusercontent.com/109751694/209457353-69bf0650-5066-4828-ace6-dfea526f109b.png)

Portion of the training set causes different values of estimation accuracy while
training the model and the values of the accuracy changes according to the increase in the portion
every iteration and the lines between testing the model every iteration using the test set and
validation set shows the change of values. K value affect the model as we can see on the figure.
Increasing the value of K improve the model ability to predict better, as large K value would be
better to get low variance and high bias and small K cause high variance and unstable output.
The first case where [k=2,sample=100] the smaller k with the smaller chunk of data causes unstable
output and confuses the model so it takes long time as shown in the figure above which is “time1”
.In the other hand, the same K with the larger chunk of data takes short period to predict “time2”.
The other cases, time wasn’t the same when we use [k=10] with different chunks
[sample=100,1000] obtaining prediction takes shorter period with the smaller chunk where the
larger K increases the computational expense so it requires more time with the larger chunk.
