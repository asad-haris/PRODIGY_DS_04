# Twitter Sentiment Analysis: Understanding Public Opinion on Social Media

## Internship Task  
**Organization:** Prodigy InfoTech  
**Internship Track:** Data Science  
**Task Number:** Task-04  
**Project Type:** Natural Language Processing & Sentiment Analysis  
**Difficulty Level:** Intermediate  

---

## 📌 Project Overview
This project focuses on analyzing and visualizing sentiment patterns in social media data to understand public opinion and attitudes toward specific topics and brands. The objective is to process real Twitter data, classify sentiments, identify trends, and extract meaningful insights about how different entities are perceived online.

The task emphasizes text preprocessing, sentiment classification, visual exploration, and business-relevant insight generation from unstructured social media content.

---

## 📂 Dataset Information
- **Source:** Prodigy InfoTech GitHub Repository – Social Media Sentiment Dataset  
- **Dataset Link:**  
  https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204  

The analysis uses two combined Twitter datasets containing labeled sentiments across various topics and brands:

- **Primary Files:** `twitter_training.csv` and `twitter_validation.csv`
- **Target Variable:** `Sentiment`  
  - `Positive` → Favorable opinion  
  - `Negative` → Unfavorable opinion  
  - `Neutral` → Neutral or factual statement  
  - `Irrelevant` → Not applicable to sentiment analysis  
- **Key Entities:** 32 topics/brands including gaming companies, tech firms, and consumer products

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Matplotlib & Seaborn  
- NLTK (Natural Language Toolkit)  
- Regular Expressions (re)  
- WordCloud  
- Google Colab  

---

## 🔄 Project Workflow

### 1. Data Loading & Integration
- Loaded and combined both Twitter datasets (`training` and `validation`).
- Verified data structure, column assignments, and sentiment labels.
- Created a unified dataset of approximately 75,000 tweets for comprehensive analysis.

### 2. Data Cleaning & Preprocessing
- Handled missing values in text and metadata.
- Applied text normalization: lowercase conversion, URL removal, special character cleaning.
- Filtered and standardized entity names and sentiment categories.
- Ensured data quality for reliable sentiment analysis.

### 3. Exploratory Data Analysis (EDA)
- Analyzed overall sentiment distribution across the dataset.
- Identified most-discussed entities (topics/brands).
- Examined sentiment patterns for top entities through aggregated statistics.
- Generated visualizations to illustrate sentiment trends and distributions.

### 4. Sentiment Pattern Analysis
- Calculated sentiment percentages for each entity.
- Identified entities with predominantly positive, negative, or neutral reception.
- Analyzed word usage patterns within different sentiment categories.
- Extracted common themes and vocabulary associated with each sentiment.

### 5. Insight Generation & Visualization
- Created multiple visualization types: bar charts, pie charts, heatmaps, word clouds.
- Synthesized findings into actionable insights about public perception.
- Developed entity-specific sentiment profiles and comparative analysis.

---

## 📊 Visualization Details
- **Sentiment Distribution:** Bar chart and pie chart showing overall sentiment breakdown
- **Top Entities Chart:** Horizontal bar chart of most-discussed topics/brands
- **Sentiment by Entity:** Stacked bar chart showing sentiment composition per entity
- **Sentiment Heatmap:** Color-coded matrix of sentiment percentages across entities
- **Word Clouds:** Visual representations of common terms by sentiment category

These visualizations effectively communicate public opinion patterns and sentiment trends.

---

## 💡 Key Insights
- Social media sentiment varies significantly across different entities, with some brands/topics receiving predominantly positive reception while others face more critical discourse.
- The most-discussed entities in the dataset represent a mix of gaming, technology, and consumer product categories.
- Positive sentiment is often associated with product features, user experience, and entertainment value.
- Negative sentiment frequently relates to technical issues, service problems, or unmet expectations.
- Neutral sentiment commonly appears in informational posts, updates, and factual discussions.
- Word analysis reveals sentiment-specific vocabulary patterns that can inform content strategy and customer engagement approaches.

---

## ⚠️ Limitations
- The dataset represents a specific snapshot in time and may not reflect current sentiment trends.
- Automated sentiment classification has inherent limitations in understanding sarcasm, irony, and nuanced language.
- The analysis focuses on aggregated patterns rather than individual tweet-level sentiment accuracy.
- Some entities have limited sample sizes, affecting the reliability of their sentiment profiles.

---

## 🔗 LinkedIn Post
The completion of this task and key learnings have been shared on LinkedIn as part of the internship requirements.

**LinkedIn Post Link:**  
(Add your Task-04 LinkedIn post URL here)

---

## ✅ Task Status
- Task completed according to Prodigy InfoTech guidelines.
- Both provided datasets successfully loaded, cleaned, and analyzed.
- Comprehensive sentiment analysis performed with appropriate visualizations.
- Meaningful insights extracted about public opinion toward various topics and brands.
- Professional documentation and code organization maintained.
- Notebook executed successfully in Google Colab.

---

## 📁 Project Structure
```text
PRODIGY_DS_04/
│
├── PRODIGY_DS_04.ipynb          # Complete sentiment analysis notebook
├── README.md                     # Project documentation (this file)
├── requirements.txt              # Python dependencies
│
└── assets/                       # Key visualizations (sample)
    ├── sentiment_distribution.png
    ├── top_entities.png
