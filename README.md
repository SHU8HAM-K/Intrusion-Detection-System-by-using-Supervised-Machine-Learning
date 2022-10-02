# Intrusion-Detection-System-by-using-Supervised-Machine-Learning
Using three different machine learning algorithm to detect intrusion in network and make a comparison that which algorithm is best between them.

I used Pandas, Numpy, Matplotlib, Seaborn, Sklearn, MinMax Scaler module of Sklearn, Train Test Split, Decision Tree, Support Vector Machine and Logistic Regression from sklearn module to create this project.

I used KDD's 99 Dataset from Kaggle.

By using Correlation and Heatmap I drop the unnecessary attributes.

Some Categorical attributes are highly correlated with the target column, So I map it.

For Training 67 % of data is used and for testing rest of 33 % are used.

Decision tree takes 1.8086 for training and 0.0927 testing time and give 99.0582 % train score with 99.0523 % test score. 

Support Vector machine takes 184.7094 for training and 102.1106 for testing time and give 99.8755% train score with 99.8791% test score.

Logistic regression takes 84.9530 for training and 0.0688 testing time and give 99.352858 % train score with 99.352867%test score.

When we do a comparison between these algorithms, we found that the decision tree takes less training and testing time. Support Vector 
Machine has the highest accuracy as we compared it with Decision Tree and Logistic Regression.

So according to less time decision tree is good for our KDD’99 dataset and if we 
talk about accuracy then Support Vector Machine. 

I wrote a thesis paper on this and this the the ABSTRACT of my project.

The whole world is joining the Internet because our world moving towards 
digitalization. Internet/Networks are significant today on the planet and 
information security has turned into a pivotal area of study. As the number of users 
of the Internet is increasing, it has become a challenge to provide that network 
security. Nowadays the improvement of organization security is subsequently 
featured. Assurance of the Network permits the accidental impedance to a structure 
to arrange and stay away from it. Intrusion Detection System (IDS) is one of the 
most essential security tools for many security concerns existing in today's cyber 
world. Intrusion Detection System is constructed to examine the system 
applications and network traffic to reveal suspicious activities and issue a warning 
if it is found. To create a more perfect system, countless strategies are accessible in 
AI for intrusion detection. The main objective of this paper is to perform anomaly
based intrusion detection systems and apply different machine learning algorithms 
to the data set and compare and evaluate their performances.

In this paper, we use the KDD’99 cup dataset and Pearson's Correlation 
method to select the important features from the dataset and remove those features 
that are useless in finding the accuracy. The preprocessed dataset tried with the 
models to get the noticeable outcomes, which prompts expanding the expectation 
precision. Machine learning methods, such as Decision Trees, Support Vector 
Machine, Logistic Regression were used. The examination provides a predictive 
computational methodology to boost intrusion detection in the Network Traffic 
Data along with applying different approaches for the appraisal of the best accuracy 
from the Machine Learning. The results of different classification algorithms 
compared at last by using the proposed dataset have been presented in the paper for 
their serviceability.
