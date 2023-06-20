# Prediction Of Essay Scores

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
In this assignment, we utilized Python and various libraries to perform predictive analytics on the dataset "FIT1043-Essay-Features.csv". Our objective was to predict students' essay scores based on their essay features. We successfully implemented Support Vector Machine/Regression models and followed a series of steps including train-test split, feature engineering, normalization, model fitting, and evaluation.

Through our analysis, we obtained valuable insights into the relationships between essay features and scores. The predictive models demonstrated satisfactory performance, as indicated by accuracy, quadratic weighted kappa, and the confusion matrix. The model was then used to predict essay scores for another dataset and submitted the results to Kaggle.

Overall, this assignment provided hands-on experience with predictive analytics techniques and demonstrated the application of Python and relevant libraries in data analysis and machine learning. By understanding the factors that influence essay scores, we can gain deeper insights into the evaluation process and potentially contribute to improving educational assessments.

We employed various libraries such as Numpy, Pandas, Matplotlib, Scikit-learn, and Seaborn, which facilitated data manipulation, visualization, and model implementation. These tools proved to be instrumental in achieving our analysis goals.

Through this project, we enhanced our skills in data wrangling, feature engineering, model selection, and evaluation. We also gained a better understanding of the importance of data exploration, preprocessing, and choosing appropriate evaluation metrics. This assignment provided a valuable opportunity to apply theoretical knowledge to real-world data and contribute to the field of predictive analytics.

By completing this assignment, we have gained a solid foundation in predictive analytics and are well-equipped to tackle similar projects in the future.
