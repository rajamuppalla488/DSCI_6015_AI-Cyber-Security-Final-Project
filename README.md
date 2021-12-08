## DSCI_6015_AI-Cyber-Security-Final-Project


### This is the network intrusion detection dataset which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes. For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .

The class variable has two categories: • Normal • Anomalous

The data preprocessing techniques used in this project were like standardizing data,analyzing,converting the object types in to the numeric datatypes by using LabelEncoder() method.In addition,to that Correlation matrix was helpful for extracting the essential features.

for splitting the data Train-Test split method was used 70% of that data is used is for training set and 30% is used for testing set finally, Evaluation metrics used were precision,f1_score,accuracy,recall,confusion matrix

precision The precision is the ratio tp / (tp + fp) where tp is the number of true positives and fp the number of false positives. The precision is intuitively the ability of the classifier not to label as positive a sample that is negative. The best value is 1 and the worst value is 0.

F1_score The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0. The relative contribution of precision and recall to the F1 score are equal. The formula for the F1 score is: F1 = 2 * (precision * recall) / (precision + recall)

Recall The recall is the ratio tp / (tp + fn) where tp is the number of true positives and fn the number of false negatives. The recall is intuitively the ability of the classifier to find all the positive samples.

Results were analyzed as KNN Classifier:0.99 Logistic Regression:0.95 Naive Bayes:0.90 Decision tree:0.98

Youtube Link Description is here https://youtu.be/mQQy4SO8nLE
