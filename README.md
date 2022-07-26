# E-Mail Classification ML Model

**GOAL:**
Classify emails as spam or not-spam on the basis of the message.

**DATASET:**
[E-Mail classification NLP](https://www.kaggle.com/datatattle/email-classification-nlp)

**WHAT I HAD DONE:**

I have started with simple Exploratory Data Analysis(EDA), looked for some null or duplicate vales. 
Then splited the training and testing dataset using sklearn. 
Then I implemented different models to classify the message as spam or not-spam.

**MODELS USED:**
1. Naive Bayes (Multinominal)
2. Random Forest Classifier
3. XG Boost Classifier

**LIBRARIES NEEDED:**
1. Numpy
2. Pandas
3. Sklearn

**CONCLUSION:**
| Models | Accuracy on Training Set  | Accuracy on Testing Set |
|:-----|:--------:|:------:|
| Naive Bayes (Multinominal) | 0.99346 | 0.96875 |
| Random Forest Classifier | 1.0 | 0.91666 |
| XG Boost Classifier | 0.97908 | 0.95833 |


| Naive Bayes (Multinominal) Training Set Accuracy  | Naive Bayes (Multinominal) Testing Set Accuracy |
|:--------:|:------:|
