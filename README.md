# Samsung-Innovation-Campus-project
## Project Description:
This research for Samsung Innovation Campus as a final project that intends to detect fake news stories through the use of Natural Language Processing (NLP) approaches and three different machine learning algorithms: Random Forest, K-Nearest Neighbors (KNN), and Naive Bayes. The dataset for this project is a collection of articles from the Kaggle Fake News Competition.

The following steps are involved in the project:


### Data Preparation:

Stop words, punctuation, and non-alphabetic letters are removed from the raw text data. After that, the text data is tokenized, lemmatized, and lowercased.


### Extraction of Features:

The Bag-of-Words model is used to turn the preprocessed text input into numerical feature vectors. Each document is represented by this model as a vector of word frequencies.

### Model Training:
Using the feature vectors, the Random Forest, KNN, and Naive Bayes algorithms are trained to construct classifiers that can determine whether a news story is phoney or authentic based on its text content.

### Model Evaluation:
The three classifiers' accuracy is assessed using cross-validation and performance indicators such as precision, recall, and F1 score.

### Model Comparison:
The performance of the three classifiers is compared to discover which algorithm is best at detecting fake news.

### The project uses three models to detect fake news:
Random forest - KNN - Naive Bayes
