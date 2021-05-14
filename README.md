# Product-Analyzer
### Problem Statement

Amazon is an online shopping website that now caters to millions of people everywhere. Over 34,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided. The dataset has attributes like brand, categories, primary categories, reviews.title, reviews.text, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted. You are required to predict Sentiment or Satisfaction of a purchase based on multiple features and review text. Dataset Snapshot

### Class Imbalance Problem:

#### Perform an EDA on the dataset.

#### a)  See what a positive, negative, and neutral review looks like

#### b)  Check the class count for each class. It’s a class imbalance problem.
#### Convert the reviews in Tf-Idf score.

#### Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.

### Tackling Class Imbalance Problem:

#### Oversampling or undersampling can be used to tackle the class imbalance problem. In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project. Use Tree-based classifiers like Random Forest and XGBoost. Note: Tree-based classifiers work on two ideologies namely, Bagging or Boosting and have fine-tuning parameter which takes care of the imbalanced class.
### Model Selection:

#### Apply multi-class SVM’s and neural nets. Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB. Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.

### Applying LSTM:

#### Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.)

  2. Compare the accuracy of neural nets with traditional ML based algorithms.

  3. Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral. 

   Hint: Use techniques like Grid Search, Cross-Validation and Random Search
   Topic Modeling:

