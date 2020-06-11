# Quora Insincere Question Detection

Quora is a public question answer forum where anyone with an account can post questions or answers related to various topics, 
such as science, religion, politics, sports etc. With such a wide range of topics being discussed without any sort of 
regulation, quite often we observe questions or answers with insincere tones to them, i.e., questions or answers that 
are not neutral in nature, contains direct or indirect discrimination against some demography, or absurdity that is not 
grounded in reality. In this project, we aimed to build a binary classification model that successfully classifies 
Quora Texts into “sincere” and “insincere”. We worked with a dataset provided by Quora on Kaggle, and fit various 
supervised and unsupervised machine learning classification models on the dataset. We compared the models on their ability 
to predict “sincere” vs “insincere” text on unseen data, and found out that Long Short Term Memory Recurrent Neural Networks
(LSTM RNNs) gives the best results.
