# Personalized-cancer-diagnosis


PERSONALIZED CANCER DIAGNOSIS!! SOURCE:https://www.kaggle.com/c/msk-redefining-cancer-treatment

Objective: Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

Business constraints: 
1.errors can be costly 

2.interpretability is very important 

3.No low latency is required

Data Overview:

1.training_variants (ID , Gene, Variations, Class) 

2.training_text (ID, Text)

Performance matrix: 

1.multi class log-loss 

2.confusion matrix



Classify the given genetic variations/mutations based on evidence from text-based clinical literature.


- One dataset contains the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations. 


- Implemented Logistic regression with CountVectorizer Features, including both unigrams and bigrams.
