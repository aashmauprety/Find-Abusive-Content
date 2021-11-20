> This project trains a model that can identify the abusive content in any text. This is trained using NLTK library using **Gaussian Naive Bayes Algorithm"** 
on a corpus of dataset containing 
offensive and abusive words.

> **"bad_words.csv"** is the dataset used in this project.

The steps followed in this project are summarized as below:

 * Read the bad_words.csv file using pandas.
 * Pre-procesing and Cleaning of the dataset by removing stopwords and stemming.
 * Create Bag of Word Model using CountVectorizer
 * Split the pre-processed dataset into traing and testing data
 * Training Gaussing Naive Bayes model using training dataset
 * Testing the results of the model using test dataset
              
