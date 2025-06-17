# IMDB Sentiment Analysis on Movie Reviews

## Overview

This project scrapes movie reviews from IMDB for sentiment analysis using **NLP techniques** and **machine learning** models.  
It aims to classify reviews as **positive** or **negative** based on their content.

### Objective:
- Scrape **user reviews and ratings** from IMDB.
- Preprocess text by removing **stopwords**, applying **stemming**, and **tokenizing**.
- Perform sentiment analysis with **VADER** (rule-based) and **machine learning models** (SVM, Decision Tree).
- Evaluate and compare the performance of the classifiers using **accuracy**, **precision**, **recall**, and **F1-score**.

## 🔗 URLs Scraped

The following movies were used for scraping reviews:
1. [Schindler's List](https://www.imdb.com/title/tt0108052/reviews?ref_=tt_urv)
2. [House of the Dead](https://www.imdb.com/title/tt0317676/reviews?ref_=tt_urv)
3. [Sharper (2023)](https://www.imdb.com/title/tt12573454/reviews?ref_=tt_urv)
4. [777 Charlie](https://www.imdb.com/title/tt7466810/reviews?ref_=tt_urv)
5. [Double Indemnity](https://www.imdb.com/title/tt0036775/reviews?ref_=tt_urv)
6. [Infinity Pool (2023)](https://www.imdb.com/title/tt10365998/reviews?ref_=tt_urv)
7. [Rang De Basanti](https://www.imdb.com/title/tt0405508/reviews?ref_=tt_urv)

## 🧰 Tools & Libraries Used

- **Python** (for scraping, preprocessing, and modeling)
- **BeautifulSoup** (for web scraping)
- **NLTK** (for text preprocessing)
- **VADER** (for rule-based sentiment analysis)
- **Scikit-learn** (for machine learning models like **SVM** and **Decision Trees**)
- **Pandas** (for data manipulation)

## 📂 Project Files

1. **`IMDB_Sentiment_Analysis.ipynb`** – Jupyter notebook with complete analysis: data collection, preprocessing, model building, and evaluation.
2. **`requirements.txt`** – Contains the libraries used in this project (for easy setup).
3. **`IMDB_reviews.csv`** – (Optional) Scraped reviews in CSV format (if needed).

## 📥 Getting Started

### Prerequisites:
Ensure you have Python 3.x installed. You’ll need the following libraries to run the notebook:

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Download or clone the repository.

3. Run the notebook `IMDB_Sentiment_Analysis.ipynb` in Jupyter or Google Colab.

### Running the Notebook:
- Open the notebook in **Google Colab** or **Jupyter Notebook**.
- Run the cells one by one.

## 📊 Evaluation

The project uses **VADER** and **SVM**/**Decision Tree** for sentiment classification. We evaluate:
- **Accuracy**, **Precision**, **Recall**, and **F1-Score** to compare the models' performance.
- **SVM** showed better overall performance, especially in terms of **precision**.

## 🎯 Key Insights

- **SVM** outperformed the **Decision Tree** classifier in accuracy and precision.
- Misclassifications often occurred in reviews with **mixed sentiments** or **sarcasm**.
- The project demonstrates how **NLP techniques** can be used for **real-world applications** like customer feedback analysis.

---

### 🔄 Next Steps

- **Enhance the data collection** by adding more movie URLs and reviews.
- **Deploy models** for real-time sentiment analysis.
- Experiment with **more advanced models** like BERT for better results.

## 🔗 Link to GitHub Repository

[View the Code on GitHub](https://github.com/akhtaranease/IMDB-Sentiment-Analysis)
