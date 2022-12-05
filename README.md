# NLP MovieReview Classification
## Task:
  To create a model that classifies given reviews as positive or negative
## Dataset:
  The dataset is obtained from http://ai.stanford.edu/~amaas/data/sentiment/
## Approach:
  1. Imported the dataset
  2. Checked for null values and whitespaces
  3. Dropped the columns with null values and whitespaces
  4. Splitted the dataset into train and test
  5. Created a pipeline with two functions
      * to transform text into vector using TFIDF Vectorization
      * to train data using LinearSVC method
  6. Trained the model using train dataset
  7. Predicted the result for test dataset
  8. Analyze the results with confusion_matrix, classification_report and accuracy_score
  9. Obtained result of 92%
