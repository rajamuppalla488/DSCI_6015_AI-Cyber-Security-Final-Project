## DSCI_6015_AI-Cyber-Security-Final-Project


##### This project is about the network intrusion detection in DNS Traffic. 

##### The Dataset which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. 

##### The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes. For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data.

##### The class variable has two categories: (1) Normal (2) Anomalous.

##### Data preprocessing techniques used in this project were like standardizing data, analyzing, converting the object types in to the numeric datatypes by using LabelEncoder() method.

##### For Train-Test split, 70% of that data is used is for training set and 30% is used for testing set. 
##### Evaluation metrics used were precision, F1_score, Accuracy, Recall, Precision and Confusion matrix.

##### Precision is the ratio tp / (tp + fp) where tp is the number of true positives and fp the number of false positives. The best value is 1 and the worst value is 0.

##### F1 score can be interpreted as a weighted average of the precision and recall. The formula for the F1 score is: F1 = 2 * (precision * recall) / (precision + recall)

##### Recall is the ratio tp / (tp + fn) where tp is the number of true positives and fn the number of false negatives.

##### The Presentation Youtube Link is https://youtu.be/XOES5QhCD-g
