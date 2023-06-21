# Prediction Of Essay Scores

Author: Kuah Jia Chen

## About
The objective of this assignment is to perform predictive analytics using Support Vector Machine/Regression in Python's Jupyter Notebook environment. The dataset used for this assignment is "FIT1043-Essay-Features.csv". The assignment aims to predict students' essay scores based on their essay features. The process includes a train-test split, feature engineering, normalization, model fitting, and evaluation using accuracy, quadratic weighted kappa, and a confusion matrix. Additionally, the model will be used to predict essay scores for another dataset and submit the results to Kaggle.

## File Description
- "FIT1043-Essay-Features.csv": Dataset for model building. [Source](https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
- "FIT1043-Essay-Features-Submission.csv": Dataset for score prediction. [Source](https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
- "99999999-YourName-1.csv": Sample submission file in the correct format. [Source](https://www.kaggle.com/c/mum-fit1043-s1-2021/data)
- "32286988-KuahJiaChen.csv": My prediction for the submission file.

## Data Fields
- essayid: Unique ID to identify the essay
- chars: Number of characters in the essay, including spaces
- words: Number of words in the essay
- commas: Number of commas in the essay
- apostrophes: Number of apostrophes in the essay
- punctuations: Number of punctuations (excluding commas, apostrophes, periods, and question marks) in the essay
- avg_word_length: Average length of words in the essay
- sentences: Number of sentences in the essay (determined by periods/full stops)
- questions: Number of questions in the essay (determined by question marks)
- avg_word_sentence: Average number of words in a sentence in the essay
- POS: Total number of Part-of-Speech discovered
- POS/total_words: Fraction of POS in the total number of words in the essay
- prompt_words: Words related to the essay topic
- prompt_words/total_words: Fraction of prompt words in the total number of words in the essay
- synonym_words: Synonymous words
- synonym_words/total_words: Fraction of synonymous words in the total number of words in the essay
- unstemmed: Number of words that were not stemmed in the essay
- stemmed: Number of words that were stemmed (cut to the base word) in the essay
- score: Rating grade ranging from 1 to 6 (label for supervised learning)

## Libraries Used
- Numpy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

## Conclusion
Overall, this assignment provided me with a clear understanding of how predictive analytics works and offered a great experience in data visualization. I utilized Support Vector Regression (SVR) as the model for prediction. One of the main challenges I encountered was determining the most effective features for prediction. The selection of feature columns significantly impacts the model's performance, making it crucial to choose the right essay features to enhance the model.

I also realized the importance of the confusion matrix and classification report, which allowed me to visualize the model's performance in a detailed manner. These tools provided valuable insights into the model's accuracy and effectiveness. Throughout this assignment, I gained a better understanding of various concepts, such as supervised learning, labeled data, training and testing datasets, binary and multi-class classification, as well as Support Vector Machine/Regression (SVM/SVR) and their respective kernels.

Additionally, this assignment provided me with an opportunity to participate in a Kaggle competition, further enhancing my practical experience in predictive analytics.

In conclusion, this assignment not only improved my knowledge and skills in predictive analytics, but it also allowed me to apply these concepts in a real-world scenario, solidifying my understanding of the subject matter.
