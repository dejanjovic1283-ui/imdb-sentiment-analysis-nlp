# IMDB Sentiment Analysis (NLP)

This project demonstrates a professional Natural Language Processing (NLP) pipeline for sentiment analysis using the IMDB movie review dataset.

## Objective
Classify movie reviews as **positive** or **negative** using machine learning.

## Technologies Used
- Python
- pandas
- scikit-learn
- NLTK
- TF-IDF Vectorization
- Logistic Regression
- GridSearchCV

## Features
- Text preprocessing (cleaning, stopwords removal)
- TF-IDF feature extraction
- Hyperparameter tuning with GridSearchCV
- Model evaluation (accuracy, classification report)
- Confusion matrix visualization
- Custom prediction function
- Model saving with joblib

## Results
- Accuracy: ~90%
- Strong generalization on unseen data

## Example Predictions

| Review | Prediction |
|------|-----------|
| "Amazing movie!" | Positive |
| "Worst film ever." | Negative |

## Project Structure
- Notebook: `imdb_sentiment_analysis_nlp.ipynb`
- Model: `imdb_sentiment_model.pkl`

## Conclusion
This project demonstrates a complete NLP pipeline and is suitable for machine learning and data science portfolios.
