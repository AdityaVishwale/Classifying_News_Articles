# Classifying_News_Articles
- This project focuses on building an automated multi-class text classification system that categorizes news headlines into predefined categories such as Politics, Sports, Business, Technology, and Entertainment. With the rapid growth of digital news platforms, manually organizing large volumes of news content becomes inefficient.
- This project demonstrates how Natural Language Processing (NLP) techniques combined with machine learning and deep learning models can effectively solve this problem.
- The system processes raw news headlines, cleans and transforms textual data, and learns meaningful patterns to accurately assign the correct news category. Two different modeling approaches are implemented and compared to analyze performance and trade-offs between traditional and neural network-based methods.

# Objective of the Project
- To automatically classify news headlines into multiple categories.
- To compare classic machine learning models with deep learning models.
- To evaluate model performance using standard classification metrics.
- To understand misclassification patterns through visual analysis.

# Methodology
## 1. Data Preprocessing
- Converted text to lowercase.
- Removed punctuation, numbers, and stopwords.
- Tokenized headlines for model input.
- Encoded categorical labels into numerical form.
## 2. Feature Engineering
- TF-IDF Vectorization for classical machine learning.
- Tokenization & Padding for deep learning models.
## 3. Model Development
Model 1: TF-IDF + Logistic Regression.
- A traditional machine learning approach.
- Efficient and interpretable.
- Performs well on short text such as headlines.
#
Model 2: LSTM Neural Network
- Captures sequential and contextual word patterns.
- Uses word embeddings for semantic understanding.
- Designed to handle complex language structures.

# Model Evaluation
Models were evaluated using:
- Accuracy.
- Precision, Recall, and F1-score.
- Confusion Matrix for error analysis.
- Word Clouds were generated to visualize dominant terms per category.
- A comparative accuracy plot was used to analyze model performance.

# Key Results & Findings
- TF-IDF + Logistic Regression achieved strong performance on headline classification.
- LSTM model learned deeper contextual relationships but required more training time.
- Classical ML models proved highly effective for short-text classification.
- Most misclassifications occurred between semantically similar categories (e.g., Politics & Business).

# Conclusion
- This project demonstrates the effectiveness of NLP-based text classification for real-world applications such as news aggregation and content recommendation. It highlights the strengths of both traditional machine learning and deep learning approaches and emphasizes the importance of preprocessing and feature selection in text-based tasks.

The system can be extended further by incorporating advanced embeddings (Word2Vec, BERT), hyperparameter tuning, or real-time deployment using web frameworks.

## Technologies & Tools Used
- Programming Language: Python.
- Libraries:
  Pandas, NumPy,
  NLTK,
  Scikit-learn,
  TensorFlow / Keras,
  Matplotlib, Seaborn.
- Development Environment: Jupyter Notebook.
