# Movie Reviews Sentiment Analysis
## Project Description
This project aims to classify movie reviews into positive and negative sentiments using Natural Language Processing (NLP) techniques. The goal is to analyze the textual data from movie reviews and predict whether the sentiment of a review is positive or negative. This is achieved using binary classification models after extracting useful features from the text data.

## Technologies Used
* Programming Language: Python  
* Libraries/Frameworks:
   * NLP: NLTK, spaCy
   * Machine Learning: Scikit-learn
   * Data Handling: pandas, NumPy
   * Visualization: Matplotlib, Seaborn

## Dataset
The dataset consists of movie reviews, where each review is labeled as either "positive" or "negative." The dataset can be obtained from various open sources, such as Kaggle's IMDb reviews dataset or other movie review datasets.

## Coding Sections
In this part we will see the project code divided to sections as follows:

* Section 1 | Data Preprocessing :
In this section we aim to do some operations on the dataset before training the model on it,
processes like :

   * Loading the dataset
   * Encoding ouput to binary (Positive : 1 , Negative : 0)
   * Data cleaning : Remove HTML tags
   * Data cleaning : Remove special characters
   * Data cleaning : Convert everything to lowercase
   * Data cleaning : Remove stopwords
   * Data cleaning : Stemming
    
* Section 2 | Model Creation :
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.

* Section 3 | Model Evaluation :
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.
