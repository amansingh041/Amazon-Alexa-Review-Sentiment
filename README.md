## Amazon Alexa Review Sentiment Analysis

This project performs sentiment analysis on Amazon Alexa product reviews using Natural Language Processing (NLP) techniques and machine learning. It classifies reviews as positive or negative based on textual content.

The model is trained on a labeled reviews dataset and applies text preprocessing, feature extraction, and classification algorithms to achieve high accuracy.

### Live Demo : https://amazon-alexa-review-webapp.onrender.com

### Project Overview
This project builds a robust text classification system using NLP and Machine Learning. It processes raw text, converts it into numerical features using TF-IDF, and predicts sentiment effectively.


### Key Features

Classifies text into Positive / Negative
Advanced text preprocessing:
    Lowercasing
    Tokenization
    Stopword removal
    Wordnet Lemmatization
    Feature extraction using TF-IDF Vectorization
Multiple ML models implemented:
    Bernoulli Naive Bayes
    Multinomial Naive Bayes
    Support Vector Classifier (SVC)
    Random Forest Classifier
    Extra Trees Classifier
Performance evaluation:
    Accuracy
    Precision
    Recall
    Confusion Matrix

### Project Workflow
1. Data Collection (SMS Dataset)
2. Data Cleaning & Preprocessing
3. Text Normalization (Wordnet Lemmatization)
4. Feature Extraction (TF-IDF)
5. Model Training
6. Model Evaluation
7. Prediction on New Data

### Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
NLP (Natural Language Processing)

### Model Performance 
Random Forest Classifier Model
    Training Accuracy: 99.00%
    Testing Accuracy: 94.92%
    Precision: 95.65%
    Recall: 98.96%

### Future Improvements
Deploy as a web application using Flask
Real-time sentiment analysis system
Implement Deep Learning models 
Improve handling of imbalanced datasets 

### Use Cases

1. Customer feedback analysis
2. Product improvement insights
3. Brand sentiment monitoring
4. NLP-based classification systems

### Conclusion

This project demonstrates how Machine Learning and NLP can be effectively applied to analyze text data and extract meaningful insights, showcasing practical skills in building and evaluating real-world ML models.