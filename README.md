**Botnet detection**
Intrusion detection on device network 

Botnet network is a sophisticated network of bots used
by cyber criminals to launch malicious activities over the
internet. Botnet based attack is one of the major challenges
on network devices. Detection of attack in network device is notably distinct
since it requires specific requirements for instance low
latency, mobility, and distributed nature. Botnet size varies
from small botnet consists of few hundred bots to the large
botnets with 50,000 hosts. Hackers spread botnet malware
and operate secretly without any noticeable indication of their
presence and can remain effective and functioning for years
Current security systems greatly depend on mathematical
models which often do not signify the systems accuracy and
appropriate security in wireless environment requires hefty
mathematical solutions which causes long computational time
and create complexity . Machine learning algorithms will
therefore undertake a crucial part in IoT security system, since
it is effective in modelling systems that cannot be introduced
by a mathematical equations.

**1. Data preprocessing**
Data preprocessing is the first and one of the most important
stages in building machine learning model. Bad data can
produce inaccurate result. To get correct output at very first
stage, dataset is analyzed, and formatting is done. 

**2. Feature Engineering**
Feature engineering technique is applied as a part of
machine learning approach which helped in dimensionality
reduction which thereby minimized the problem of over-fitting.
This improved accuracy, and significantly reduced processing
time. Also, it was beneficial in selecting appropriate features
that contain most important information about target variable
and helped to improve the performance of model.

**C**. Synthetic Minority over-sampling technique (SMOTE)
SMOTE is one of the effective techniques to make class
balance dataset. Imbalanced dataset may cause misclassifying
problems which effect on the performance of machine learning
algorithms. Thereforem teh dataset which was initailly imbalanced was balanced with this technique


**D** Comparison of performance of Machine learning algorithms
In this Botnet detection model, we combined feature engineering

1) Results with Random Forest  model:  For
the dataset, the accuracy result from RF is good.
This indicates that the RF classifier is effective algorithm in
botnet detection system. The accuracy is 97.5% and both the precision and recall  is 99.1% and 96% respectively 

2) Results with Gaussian Naïve bayes model: As seen for the dataset, with Gaussian Naïve bayes
algorithm, we observed  a low score of 86% accuracy,
and  81% precision respectively.However we got a 93% recall score.
This shows that Gaussian Naive bayes is not effective on bot-net detection.

3)Results with KNN model: As presented it is clear
seen that KNN accuracy is 97.6% percent with a high  value in
precision (95.9%), recall(99%),  and f1-score (97.5%),. This showed
that the accuracy value we got from the class 
dataset is good.

4) Results with XGBOOST: After integrating XGBOOST, we
got a good value in  accuracy, precision, and recall.
 Accuracy that we got from XGBoost for the dataset is 97%, Precision is 95.7% and recall is 99.1%. This validates that XGBOOST  algorithm is a good model to
classify botnet and normal traffic.

5)Results with MLP ANN: MLP has an accuracy value of 90%, Precision of 93% and a low recall of 87%. This
evidently showed that accuracy is generally not helpful in the dataset.


**Observation**
From the above comparison, we get good and stable accuracy from all the models except MLP ANN and Naive Bayes. From
these overall comparisons on different evaluation metrics of
machine learning algorithms, KNN algorithm was found to be
the best for BoT-IoT dataset.







