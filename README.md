# Twitter Sentiment Analysis

A machine learning pipeline to classify tweets as **Positive** or **Negative** using the Sentiment140 dataset.

## 🛠️ Features
* **Model:** Logistic Regression with TF-IDF Vectorization.
* **Preprocessing:** NLTK-based cleaning (stemming, stop-word removal, URL/HTML stripping).
* **Performance:** ~79% accuracy on 1.6 million tweets.
* **Interactive:** Includes a helper function to test custom tweet inputs.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install pandas numpy seaborn matplotlib nltk scikit-learn opendatasets
   ```
2. Run: Open Twitter_Sentiment_Analysis.ipynb in Jupyter or Google Colab.
3. Data: Requires a Kaggle API key to download the Sentiment140 dataset.

⚖️ License
This project is dedicated to the public domain under the Creative Commons Zero v1.0 Universal (CC0 1.0). You can copy, modify, and distribute the work, even for commercial purposes, without asking permission.
