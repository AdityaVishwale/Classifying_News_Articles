# Classifying_News_Articles
- This project focuses on building an automated multi-class text classification system that categorizes news headlines into predefined categories such as Politics, Sports, Business, Technology, and Entertainment. With the rapid growth of digital news platforms, manually organizing large volumes of news content becomes inefficient.
- This project demonstrates how Natural Language Processing (NLP) techniques combined with machine learning and deep learning models can effectively solve this problem.
- The system processes raw news headlines, cleans and transforms textual data, and learns meaningful patterns to accurately assign the correct news category. Two different modeling approaches are implemented and compared to analyze performance and trade-offs between traditional and neural network-based methods.

# Objective of the Project
- To automatically classify news headlines into multiple categories
- To compare classic machine learning models with deep learning models
- To evaluate model performance using standard classification metrics
- To understand misclassification patterns through visual analysis

# Methodology
## 1. Data Preprocessing
- Converted text to lowercase
- Removed punctuation, numbers, and stopwords
- Tokenized headlines for model input
- Encoded categorical labels into numerical form
## 2. Feature Engineering
- TF-IDF Vectorization for classical machine learning
- Tokenization & Padding for deep learning models
## 3. Model Development
Model 1: TF-IDF + Logistic Regression
- A traditional machine learning approach
- Efficient and interpretable
- Performs well on short text such as headlines
Model 2: LSTM Neural Network
- Captures sequential and contextual word patterns\
- Uses word embeddings for semantic understanding
- Designed to handle complex language structures

