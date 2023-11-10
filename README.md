# spam-detection
SMS Spam classification using various ML Techniques.
Most common Machine Learning methods used for classification:
  Naïve Bayes Classifier Method
  K-Nearest Neighbour Classifier Method
  Logistic Regression Classifier Method
  Support Vector Machines Method
  Artificial Neural Network Method
![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/3ed86331-3e07-49de-a0fa-4b085d0e7477)

Email Corpus
![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/c3e496dc-f7f2-4718-a1c6-459eaa0d2a6b)

EDA:
Dataset was checked for missing values.
The dataset description showed there are very few emails constituting to Spam.
Almost 60% emails are Ham.
This was also plotted on a bar plot.
The text length of each email was stored.
It showed that the text length does not play any role in determining whether an email is Spam or Ham.
This can also be shown through the following plots.
![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/954fe81a-979f-43c8-8a35-605f2c61bb16)
![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/aeeb7a81-5ce0-4325-8849-b3f1742206eb)

Text Cleaning:
Removing unwanted features.
All text was converted to lower case
An unnamed column was removed
URLs were removed
Punctuations were removed

Vectorizer used : Tfidf Vectorizer
Tfidf method of vectorization is used as we are dealing with corpus on document level.
TF-IDF = Term Frequency (TF) * Inverse Document Frequency (IDF)  	      = tf(t, d) * log(N/(df + 1))

The following ML Models were used for training.
Naïve Bayes Classifier
Logistic Regression
Support Vector Machines

Metrics: Confusion Matrices of the three models.
![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/0e850cf1-4f35-43f9-8c24-89a108a9e9b6)


![image](https://github.com/SubhanshuWalia/spam-detection/assets/150337661/bd21b04e-e783-455a-a6ab-d1221b425e41)
