# Text-Classification

Multinomial Naive Bayes based Text Classification minor project taken up in the process of learning Machine Learning using Python. Used sklearn inbuilt Multinomial Naive Bayes classifier and self-written code for the same. Obtained better accuracy with self-written code. Used Jupyter Notebook (Anaconda) for ease.

## Instructions:

Download the '20_newsgroups' from 'http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups' containing the 20 directories & place it in this directory.

#### Note: To run this, you will have to change the paths in the 'Vocabulary Builder.ipynb', 'Train Database Builder.ipynb' & 'Test Database Builder.ipynb' files to this directory

1st run 'Vocabulary Builder.ipynb' to build the vocabulary of 5000 words

Next run 'Train Database Builder.ipynb' & 'Test Database Builder.ipynb' to build the training & testing datasets

Finally run 'Text Classification using inbuilt NaiveBayes.ipynb' to make predictions using the inbuilt classifier
or run 'Text Classification using self NaiveBayes.ipynb' to make predictions using self-written code



## RESULTS:

### Using inbuilt classifier:

Training - 89% precision

Testing - 85% precision

### Using self-written code:

Training - 90% precision

Testing - 87% precision
