
# 🎬 IMDb Movie Review Sentiment Analysis 🎥

Welcome to the **IMDb Movie Review Sentiment Analysis** project! This project uses the IMDb review dataset to train a model for predicting the sentiment (positive or negative) of movie reviews.

## 📂 Dataset Overview

The IMDb dataset contains **50,000** movie reviews with balanced classes for **positive** and **negative** sentiment labels.

### ⚙️ Features:
- **Review Text** - Contains the text of the review, which is preprocessed for training.
- **Sentiment Label** - Target label: `0` for negative and `1` for positive.

## 🛠️ Project Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/srivardhan-kondu/IMDB.git
   ```
2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## 🔍 Data Preprocessing

- **Tokenization** ✂️: Break down the text data into individual words or tokens.
- **Stop Word Removal** 🚫: Remove common words that do not contribute to sentiment.
- **Stemming/Lemmatization** 🌱: Reduce words to their root forms.

## 📈 Model Training

We use a **LSTM (Long Short-Term Memory)** model due to its effectiveness in text sentiment analysis.

1. **Data Split**: The dataset is split into **training** and **testing** sets.
2. **Training**: We train the LSTM model on the processed text data.
3. **Evaluation**: Evaluate accuracy, precision, and recall to assess model performance.

## 🚀 Make Predictions

To predict sentiment on a new review:
```python
review = "Your movie review text here"
sentiment = predict_sentiment(review)
print("😊 Positive" if sentiment == 1 else "😞 Negative")
```

## 📊 Results

Achieved **85% accuracy** on the IMDb test set. 🎉

## 📬 Feedback

Feel free to submit issues or pull requests. Enjoy exploring sentiment analysis with the IMDb dataset! 🌟

---

### 📜 License
This project is licensed under the MIT License.

### ✍ Contact 
srivardhan.kondu@gmail.com
