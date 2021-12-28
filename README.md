# Machine_Learning_pipelines
Here I store various machine learning solutions to different types of problems

## [NLP_multiclass_text_classification.ipynb (on Colab)](https://colab.research.google.com/drive/1MpxLRfAJKZ8th6OIaAUzWMDNck_KAI1k?usp=sharing)
This Notebook is a Multiclassification Pipeline for Text Observations
### The pipeline consists of:  
1. Gathering the data  
1. Processing the data  
1. Exploring the data  
1. Feature engineering  
1. Preliminary feature selection based on univariate proxies  
1. ML models selection  
1. Training chosen model  
1. Generating performance metrics  

### The Data:
A data set from [Hackerrank](https://www.hackerrank.com/) that holds texts and a class for each.  
There are 8 total classes for this set, so the appropriate solution is a NLP-ML classifier.

### Approach:
A simple generic ML approach.  
Meaning, I don't leverage any NLP-dedicated models (like BERT or GPT3).  
But rather I design numerical features for the various text terms (One Hot Encoding/Bag of Words/TFIDF), and pipe them into generic ML models.  
