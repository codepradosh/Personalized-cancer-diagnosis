# Personalized-cancer-diagnosis


PERSONALIZED CANCER DIAGNOSIS SOURCE:https://www.kaggle.com/c/msk-redefining-cancer-treatment

# Objective: Classify the given genetic variations/mutations based on evidence from text-based clinical literature.
Main objective of this project is to distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations. Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature. so designed a machine learning model that classifies given genetic variations/mutations based on evidence from text-based clinical literature. Got data from Kaggle which was updated by Memorial Sloan Kettering Cancer Centre. Data having some Gene, gene variations and some medical literature text related to gene variations.


# Business constraints:

1.errors can be costly 

2.interpretability is very important 

3.No low latency is required

4.Probability of a data-point belonging to each class is needed

# Data Overview:

1.training_variants (ID , Gene, Variations, Class) 

2.training_text (ID, Text)

# Performance matrix: 

1.multi class log-loss 

2.confusion matrix



Classify the given genetic variations/mutations based on evidence from text-based clinical literature.


- One dataset contains the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations. 


- Implemented Logistic regression with CountVectorizer Features, including both unigrams and bigrams.
