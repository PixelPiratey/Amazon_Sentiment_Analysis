# Amazon_Sentiment_Analysis

# 📊 Sentiment Analysis of Amazon Product Reviews (Redmi 6)

This project demonstrates how **GenAI + Python** can be used to analyze customer reviews and extract business insights.  
We performed **sentiment analysis** on 200+ Amazon product reviews of the Redmi 6 smartphone, identified customer pain points, and visualized patterns in satisfaction trends.

---

## 🔹 Project Overview
- Collected **200+ reviews** from Amazon for Redmi 6.  
- Applied **GenAI-powered prompts** and **Python NLP (VADER)** to classify reviews into **Positive, Negative, and Neutral** categories.  
- Converted **unstructured text data** into structured sentiment insights.  
- Visualized findings using **bar charts** and **word clouds** to highlight frequent themes.  
- Delivered actionable intelligence on **customer satisfaction and dissatisfaction factors**.

---

## 🔹 Tools & Technologies
- **Python** 🐍  
- **ChatGPT (GenAI Prompts)** – for generating structured summaries  
- **NLTK (VADER)** – for sentiment scoring  
- **Matplotlib & Seaborn** – for charts  
- **WordCloud** – for review visualization  
- **Pandas** – for data cleaning & processing  

---

## 🔹 Workflow
1. **Data Loading**  
   - Imported dataset `redmi6.csv` containing Amazon reviews.  

2. **Data Preprocessing**  
   - Cleaned and converted reviews into text format.  
   - Removed stopwords, punctuation, and special characters.  

3. **Sentiment Analysis**  
   - Applied **VADER Sentiment Analyzer** to assign sentiment scores.  
   - Classified each review as `Positive`, `Negative`, or `Neutral`.  
   - Used **GenAI-style prompts** to extract key themes from positive and negative reviews.  

4. **Visualization**  
   - **Bar chart**: Distribution of sentiments across all reviews.  
   - **Word Clouds**: Most frequent words in positive and negative reviews.  

5. **Output**  
   - Final dataset exported to `redmi6_sentiment_results.csv`.  

---

## 🔹 Results & Insights
- Majority of reviews were **Positive**, highlighting **value for money and good performance**.  
- **Negative reviews** focused on **battery issues and heating problems**.  
- **Neutral reviews** were mostly about **delivery experience** or **average build quality**.  
- Visualization showed clear **customer pain points** and **key satisfaction drivers**.  

---

## 🔹 How to Run
1. Install required libraries:  
   ```bash
   pip install pandas matplotlib seaborn wordcloud nltk
