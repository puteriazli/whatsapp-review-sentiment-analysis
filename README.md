## 📊 Sentiment Analysis of WhatsApp User Reviews (2025)

### 📌 Project Overview

This project analyzes **user sentiment and behavior** based on **WhatsApp application reviews** collected in **2025**.
The objective is to understand **user satisfaction trends**, **problematic app versions**, and **high-impact feedback** using **rating-based sentiment classification** and **temporal analysis**.

The project focuses on **large-scale data cleaning**, **exploratory analysis**, and **actionable insights** relevant to product and data teams.

---

### 🎯 Objectives

* Analyze user sentiment trends throughout 2025
* Identify app versions with the highest negative feedback
* Measure sentiment impact using **upvote-weighted analysis**
* Understand monthly review dynamics and rating quality
* Highlight critical user feedback with the highest influence

---

### 📂 Dataset Information

* **Source**: WhatsApp application user reviews
* **Time Period**: 2024–2025 (focus on 2025)
* **Scale**: 1,000,000+ rows
* **Key Columns**:

  * `user_id`
  * `review`
  * `rating` (1–5)
  * `upvote`
  * `datetime`
  * `app_version`

---

### 🧹 Data Preprocessing

* Removed irrelevant columns
* Renamed columns for clarity and consistency
* Converted data types (datetime, numeric, string)
* Handled missing values
* Removed duplicate reviews using multi-column validation
* Ensured data integrity before analysis

---

### 🧠 Sentiment Definition

Sentiment is derived **directly from rating values**:

| Rating | Sentiment |
| ------ | --------- |
| 1–2    | Negative  |
| 3      | Neutral   |
| 4–5    | Positive  |

This approach allows **fast, scalable sentiment analysis** without relying on language-specific NLP models.

---

### 📈 Key Analyses Performed

* Review volume trends per year and month
* App version distribution and dominance analysis
* Monthly average rating trends
* Sentiment distribution (Negative, Neutral, Positive)
* Sentiment percentage comparison per month
* December 2025 deep-dive analysis
* Identification of:

  * Most impactful negative reviews
  * Most appreciated positive features
  * Neutral feedback with high engagement
* **Upvote-weighted sentiment analysis** to measure real user impact
* Sentiment comparison across app versions
* Negative sentiment ratio per version

---

### 🔍 Key Insights

* Certain app versions show **disproportionately high negative sentiment**
* Negative reviews with high upvotes indicate **systemic user pain points**
* Average rating trends reveal **quality fluctuation over time**
* Weighted sentiment analysis highlights **what users collectively feel**, not just frequency

---

### 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

### 📌 Project Strengths

* Large-scale real-world dataset
* Strong data cleaning and validation process
* Business-oriented analysis
* Clear visualization and interpretability
* Insight-driven, not just descriptive

---

### ⚠️ Limitations

* Sentiment is inferred from ratings, not textual NLP modeling
* Review text is not tokenized or semantically analyzed
* Language-specific sentiment nuances are not captured

*(This design choice was intentional for scalability and clarity)*

---

### 🚀 Future Improvements

* Apply NLP-based sentiment modeling (TF-IDF, Word2Vec, BERT)
* Topic modeling to identify recurring issues
* Dashboard deployment (Streamlit / Power BI)
* Automated app version performance monitoring

---

### 👤 Author

**[Puteri Amelia Azli]**
Data Analyst | Data Scientist
Focused on scalable data analysis, product insight, and real-world impact.

---

### 🗓 Created

December 15, 2025

---
