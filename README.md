# Toxic_Tweets_ML
The dataset has a collection of Tweets. Its labelled as Toxic - 1, Non toxic - 0.
Applying NLP methods to predict the toxicity of the tweets. 


**Procedure:**
The dataset is downloaded from the following Kaggle Compitation https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset. 
1. Converted the CSV file to the panda data frame.
2. Converted the text to the following.
  • NLP Process- Bag of Words
  • Metrics- TF-IDF
3. For the obtained features, the following methods of prediction are applied.
  • Decision Trees
  • Random forest
  • Naive Bayes Model
  • K-NN Classifier
  • SVM
4. For each of the above methods produced the following metrics:
  • Precision, Recall, F1 - Score
  • Confusion Matrix
  • RoC - AUC curve
