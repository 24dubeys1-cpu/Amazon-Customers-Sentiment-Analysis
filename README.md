# Amazon Customer Sentiment Analysis

## 📌 Project Overview

Amazon Customer Sentiment Analysis is a Natural Language Processing (NLP) and Machine Learning project that analyzes customer reviews and classifies them into Positive and Negative sentiments. This project helps understand customer opinions and can be used to improve products and services based on user feedback.

---

## 🎯 Objective

The objective of this project is to:

- Analyze Amazon customer reviews.
- Perform text preprocessing and cleaning.
- Convert text data into numerical features using TF-IDF Vectorization.
- Train a Machine Learning model for sentiment classification.
- Predict whether a review is Positive or Negative.
- Evaluate model performance using classification metrics.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- WordCloud
- Scikit-Learn
- Jupyter Notebook / Google Colab

---

## 📂 Dataset

The dataset contains:

- Customer Reviews
- Review Ratings
- Product Information
- Sentiment Labels

### Features Used

- review_body
- star_rating

---

## ⚙️ Project Workflow

### 1. Import Libraries

Required libraries are imported for data analysis, visualization, and machine learning.

### 2. Load Dataset

The Amazon review dataset is loaded using Pandas.

### 3. Data Exploration

- View dataset structure
- Check dimensions
- Analyze columns
- Identify missing values

### 4. Data Cleaning

- Remove null values
- Remove duplicate records
- Prepare clean data for analysis

### 5. Sentiment Labeling

Reviews are classified into:

- Positive
- Negative

### 6. Text Preprocessing

Text preprocessing includes:

- Lowercase conversion
- Removal of punctuation
- Removal of stopwords
- Cleaning unnecessary characters

### 7. Exploratory Data Analysis

Visualizations include:

- Sentiment Distribution
- Rating Distribution

### 8. Word Cloud Visualization

Word clouds are generated to identify frequently occurring words in reviews.

### 9. Feature Extraction

TF-IDF Vectorization converts textual data into numerical vectors for machine learning.

### 10. Train-Test Split

Dataset is divided into:

- Training Data (80%)
- Testing Data (20%)

### 11. Model Training

Multinomial Naive Bayes classifier is used for sentiment classification.

### 12. Model Prediction

The trained model predicts sentiments for unseen reviews.

### 13. Model Evaluation

Performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

### 14. Model Saving

The trained model is saved using Pickle for future use.

---

## 📊 Visualizations

The project includes:

- Sentiment Count Plot
- Rating Distribution Histogram
- Word Cloud
- Confusion Matrix

---

## 🤖 Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is used because it performs efficiently for text classification problems and works well with TF-IDF features.

---

## 📁 Project Structure

```
Amazon-Customer-Sentiment-Analysis
│
├── Amazon_Customer_Sentiment_Analysis.ipynb
├── amazon_reviews.csv
├── sentiment_model.pkl
├── README.md
├── requirements.txt
└── images
```

---

## 📈 Results

The model successfully classifies customer reviews into positive and negative sentiments.

The project demonstrates:

- Data Cleaning
- Text Preprocessing
- Feature Engineering
- Machine Learning Model Training
- Model Evaluation
- Data Visualization

---

## 🚀 Future Improvements

- Use larger datasets
- Implement Deep Learning models
- Build a Streamlit Web Application
- Deploy the model on cloud platforms
- Perform multi-class sentiment analysis

---

## 📚 Libraries Required

```
pandas
numpy
matplotlib
seaborn
nltk
wordcloud
scikit-learn
pickle
```

---

## 👨‍💻 Author

Soumya Dubey

Computer Science Engineering Student

---

## ⭐ Conclusion

This project performs sentiment analysis on Amazon customer reviews using Natural Language Processing and Machine Learning techniques. Text data is transformed into numerical features using TF-IDF Vectorization, and a Multinomial Naive Bayes classifier is trained to predict sentiments accurately. This project provides valuable insights into customer opinions and demonstrates practical applications of NLP in business analytics.
