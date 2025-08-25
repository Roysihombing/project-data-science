# 📝 JMO App Sentiment Analysis – Google Play Store

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-orange)

## Overview
This project analyzes **50,000+ user reviews of the JMO (Jaminan Sosial Mobile) app** from Google Play Store to evaluate user satisfaction and detect application issues using **Sentiment Analysis**.

The analysis includes **data scraping, text preprocessing, sentiment labeling, and predictive modeling** with multiple machine learning models.

## Dataset
- Source: Google Play Store reviews  
- Initial dataset: 50,000 reviews → **26,792 after cleaning**  
- Labels: Positive (4–5★), Neutral (3★), Negative (1–2★)  

## Methodology
- **Scraping** using `google-play-scraper`  
- **Text preprocessing**: cleaning, deduplication, missing value removal  
- **Feature representation**: Bag of Words (BoW) & TF-IDF  
- **Models used**: Naive Bayes, Logistic Regression, Random Forest  
- **Balancing**: RandomOverSampler  

## Key Findings
- Majority reviews: **Positive (15k+)**, but login & claim process issues dominate negatives  
- **Random Forest with TF-IDF** delivered the best balance: **>91% accuracy, 91.85% F1-score**  
- Extreme ratings (1★ & 5★) dominate, moderate ratings are fewer  

## Business Solutions
- Optimize **login & claim process** with clearer flows & real-time notifications  
- Implement **chatbot support** to address FAQs  
- Monitor feedback with **sentiment model (Random Forest)** for faster improvements  
- Launch **digital education campaigns** to reduce service misunderstandings  

## Tech Stack
- **Python**: Pandas, scikit-learn, NLTK  
- **NLP**: TF-IDF, Bag of Words  
- **ML Models**: Naive Bayes, Logistic Regression, Random Forest  

## Author
**Roy Firman Sihombing**  
- [LinkedIn](https://www.linkedin.com/in/roy-firman-sihombing)  
- [GitHub](https://github.com/Roysihombing)  
- [Portfolio](https://roy-firman-sihombing.free.nf)  

---

### How to Use
1. Clone this repository  
2. Run the Python scripts for data cleaning & modeling  
3. Evaluate the sentiment classification results  
4. Use trained model to monitor new reviews automatically  

---

### License
This project is licensed under the **MIT License** – free to use and adapt.
