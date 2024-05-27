## Problem Statement
### 1. To build a custom NER to get the list of diseases and their treatment from the dataset.
### 2. To Build a model that should be able to predict the treatment for given disease.

### Task 1:
Constructed proper sentences from individual words and prints five sentences.

Correctly counted the number of sentences in the processed train and test dataset.

Correctly counted the number of lines of labels in the processed train and test datasets.

### Task 2:
Extracted those tokens that have NOUN or PROPN as their PoS tag and finds their frequency from the entire dataset that comprises both the train and the test datasets.

Print the top 25 most common tokens with NOUN or PROPN PoS tags for the entire dataset that comprises both the train and the test datasets.

### Task 3:
Defined the features with the PoS tag as one of the features.

While defining the features in which I have used the PoS tags, I also need to consider the preceding word of the current word. The use of the previous word’s information makes the CRF model more accurate and exhaustive.

Marked the beginning and end words of a sentence correctly in the form of features.

### Task4:
Created the code to compute the features' value of a sentence.

Created the code to get a list of labels of a given preprocessed label line that you have created earlier.

### Task 5:
Extracted the features' values for each sentence as an input variable for the CRF model in the test and the train datasets. Extracts the labels as the target variable for the test and the train datasets.

### Task 6:
Build the CRF model for a custom NER application.

### Task 7:
Predicted the labels of each of the tokens in each sentence of the test dataset that has been preprocessed earlier.

Calculated the f1 score using the actual and the predicted labels of the test dataset.

### Task 8:
** Created the code or logic to get all the predicted treatments (T) labels corresponding to each disease (D) label in the test dataset.

** Predicted the treatment for the disease named 'hereditary retinoblastoma'
