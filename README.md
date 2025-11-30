# 🎵 K-Pop Tweet Classification (BTS, Blackpink, NCT)

![Language](https://img.shields.io/badge/Language-Python-blue)
![Data](https://img.shields.io/badge/Data-10k+_Tweets-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Project Overview
This project focuses on **Social Media Mining** and **Text Classification** within the K-Pop community. The objective was to analyze fan engagement and build Machine Learning models capable of classifying tweets into specific fandom categories.

I successfully executed an end-to-end data science workflow, from scraping raw data to training Deep Learning models.

## 🚀 Key Achievements

### 1. Large-Scale Data Scraping
* Successfully scraped **over 10,000 tweets** from Twitter.
* Collected rich metadata including text content, user location, and engagement metrics (likes/retweets).

### 2. Preprocessing & Labeling
* Engineered a robust cleaning pipeline to handle unstructured text (removing noise, URLs, and special characters).
* Successfully labeled the dataset into three distinct classes:
    * **BTS**
    * **Blackpink**
    * **NCT**

### 3. Machine Learning & Deep Learning
Implemented and benchmarked four different algorithms to find the best classifier:
* **Naive Bayes** 
* **Logistic Regression** 
* **Multi-Layer Perceptron (MLP)** 
* **Simple Neural Network** 

## 📊 Exploratory Data Analysis (EDA)
Before modeling, I visualized the data to uncover patterns:
* **Correlation Analysis:** A heatmap revealed a strong linear relationship (>0.9) between *Favorites* and *Retweets*.
* **Distribution:** Analyzed tweet length and posting volume per fandom using Boxplots and Countplots.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow/Keras (for Neural Networks), Seaborn, Matplotlib.
* **Environment:** Jupyter Notebook / Google Colab.

