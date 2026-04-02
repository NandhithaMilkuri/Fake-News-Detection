#  Fake News Detection using Machine Learning

##  Overview

This project aims to detect whether a news article is **Fake** or **Real** using Machine Learning techniques.
It uses Natural Language Processing (NLP) and a Logistic Regression model to classify news content.


##  Features

* Data preprocessing and cleaning
* Text transformation using TF-IDF
* Machine Learning model (Logistic Regression)
* Performance evaluation using multiple metrics
* Simple and efficient implementation


##  Dataset

The dataset consists of two files:

* **Fake.csv** → Contains fake news articles
* **True.csv** → Contains real news articles

### Features:

* Title
* Text
* Subject
* Date


##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK


##  Workflow

1. Data Collection
2. Data Preprocessing

   * Removing special characters
   * Lowercasing
   * Stopword removal
   * Stemming
3. Feature Extraction using TF-IDF
4. Model Training using Logistic Regression
5. Model Evaluation


##  Model

* **Algorithm:** Logistic Regression
* **Why used?**

  * Simple and fast
  * Works well for text classification
  * Good baseline model


##  Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix


##  Results

The model achieves good performance in distinguishing fake and real news using TF-IDF features and Logistic Regression.


##  Limitations

* Depends on dataset quality
* Limited understanding of context
* Can be improved using advanced models


##  Future Improvements

* Use advanced algorithms (SVM, Naive Bayes)
* Implement Deep Learning models (LSTM, BERT)
* Deploy as a web application
* Improve accuracy with better preprocessing


## How to Run

# Clone the repository
git clone https://github.com/your-username/fake-news-detection.git

# Navigate to project folder
cd fake-news-detection

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py


##  Conclusion

Fake news detection is an important application of Machine Learning that helps reduce misinformation and improve the reliability of online content.

