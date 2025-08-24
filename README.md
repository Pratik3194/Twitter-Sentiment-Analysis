# Twitter Sentiment Analysis

## Project Description
Binary sentiment classification of tweets into **positive** or **negative**.  
A neural network was trained on preprocessed tweet text to predict sentiment labels.

## Dataset
- Columns:  
  - id → Tweet ID  
  - label → 0 = Negative, 1 = Positive  
  - tweet → Text of the tweet  

## Steps
1. Data preprocessing (cleaning text, removing stopwords, tokenization)  
2. Text vectorization (TF-IDF / Embedding)  
3. Training a neural network for classification  
4. Evaluation using Accuracy and F1-score  

## Model Used
- Feedforward Neural Network  

## Tech Stack
- Python, Pandas, NumPy  
- TensorFlow / Keras  
- NLTK / Scikit-learn  
