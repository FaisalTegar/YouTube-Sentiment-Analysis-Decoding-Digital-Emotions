# YouTube Sentiment Analysis: Decoding Digital Emotions

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![NLP](https://img.shields.io/badge/NLP-TF--IDF%20|%20NLTK-orange)

## Project Overview
As a Communication Science graduate transitioning into Data Science, I bridge the gap between human interaction and machine intelligence. This project analyzes over **17,000 YouTube comments** to classify audience sentiment into Positive, Neutral, and Negative categories.

By leveraging **Natural Language Processing (NLP)** and **Machine Learning**, this tool helps creators and brands automate community management and derive actionable content strategies.

## Tech Stack
- **Language:** Python 3.11
- **Libraries:** Pandas, NumPy, Scikit-Learn, NLTK, Emoji, Matplotlib, Seaborn
- **Model:** Tuned Random Forest Classifier (GridSearchCV)
- **Vectorization:** TF-IDF (Term Frequency-Inverse Document Frequency)

## Key Results
- **Model Accuracy:** 75.98%
- **Sentiment Distribution:** 68% Positive, 24% Neutral, 8% Negative.
- **Top Predictors:** Gratitude-based tokens ("love", "thank", "great") are the strongest drivers of positive engagement.

## Project Structure
- `data/`: Raw and cleaned datasets.
- `notebooks/`: Comprehensive EDA, Text Preprocessing, and Modeling.
- `models/`: Saved `.pkl` files for Model and Vectorizer.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to see the full pipeline.
