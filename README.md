# Prediction Of Essay Scores

## About
The objective of this assignment is to conduct predictive analytics, by using Support Vector Machine/ Regression with a dataset provided by using Python in the Jupyter Notebook environment. The dataset is “FIT1043-Essay-Features.csv”. The description of the data is as described below. The main purpose of this assignment is to make use of the dataset to predict the student's scores on essays based on their essay features. In order to achieve this, firstly, I would perform a train-test split, feature engineering, normalization, model fitting, and eventually evaluate the performance of the model created by using accuracy, quadratic weighted kappa, and confusion matrix. Afterward, the model created would be used to predict the essay score for another dataset and submit the result to Kaggle. 

## File Description
* "FIT1043-Essay-Features.csv" - the dataset to build the model (source: https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
* "FIT1043-Essay-Features-Submission.csv" - the dataset to predict the score (source: https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
* "99999999-YourName-1.csv" - a sample submission file in the correct format (source: https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
* "32286988-KuahJiaChen.csv" - my prediction for the submission file

## Data Fields
* essayid - a unique id to identify the essay
* chars - number of characters in the essay, including spaces
* words - number of words in the essay
* commas - number of commas in the essay
* apostrophes - number of apostrophes in the essay
* punctuations - number of punctuations (other than commas, apostrophes, period, questions marks in the essay
* avg_word_length - the average length of the words in the essay
* sentences - number of sentences in the essay, determined by the period (fullstops)
* questions - number of questions in the essay, determined by the question marks
* avg_word_sentence - the average number of words in a sentence in the essay
* POS - total number of Part-of-Speech discovered
* POS/total_words - fraction of the POS in the total number of words in the essay
* prompt_words - words that are related to the essay topic
* prompt_words/total_words - fraction of the prompt words in the total number of words in the essay
* synonym_words - words that are synonymous
* synonym_words/total_words - fraction of the synonymous words in the total number of words in the essay
* unstemmed - number of words that were not stemmed in the essay
* stemmed - number of words that were stemmed (cut to the based word) in the essay
* score - the rating grade, ranging from 1 - 6 (this is called the label for supervised learning)

## Libraries Used
* Numpy
* Pandas
* Matplotlib
* Scikit-learn
* Seaborn
