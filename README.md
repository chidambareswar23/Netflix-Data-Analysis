# 🎬 Netflix Movies Data Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)


---

## 🚀 Overview

This project performs **Exploratory Data Analysis (EDA)** on a Netflix movies dataset to uncover patterns in genres, popularity, ratings, and trends over time.

The analysis focuses on **data cleaning, transformation, visualization, and trend detection**, providing meaningful insights into movie distribution and audience preferences.

---

## ✨ Features

* 📊 Data cleaning and preprocessing
* 🧹 Handling missing and irrelevant data
* 🔄 Feature transformation (date conversion, categorization)
* 🎭 Genre-wise analysis (most/least frequent genres)
* ⭐ Rating-based categorization (popular, average, etc.)
* 📈 Trend analysis using linear regression
* 🔗 Correlation analysis between popularity and votes
* 📉 Visualization using Seaborn

---

## 🛠️ Tech Stack

| Category             | Tools Used |
| -------------------- | ---------- |
| Language             | Python     |
| Data Handling        | Pandas     |
| Visualization        | Seaborn    |
| Statistical Analysis | SciPy      |

---

## ⚙️ Workflow

```id="6ytflp"
Load Dataset
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Engineering (Date, Categories)
      ↓
Exploratory Data Analysis (EDA)
      ↓
Visualization (Seaborn)
      ↓
Trend Analysis (Linear Regression)
      ↓
Insights & Conclusions
```


## 📊 Key Analysis Performed

### 1️⃣ Top 5 Most Frequent Genres

Identified the most common genres available on Netflix.

### 2️⃣ Least Popular Genre

Determined the genre with the lowest number of movies.

### 3️⃣ Top 10 Most Popular Movies

Ranked movies based on vote count.

### 4️⃣ Oldest Movie

Identified the earliest released movie in the dataset.

### 5️⃣ Best Performing Year

Analyzed which year had the highest number of well-rated movies.

### 6️⃣ Correlation Analysis

Measured the relationship between:

* Popularity
* Vote count

### 7️⃣ Average Movies per Year

Calculated average number of movies released annually.

### 8️⃣ Genre Trend Analysis

Used **linear regression** to identify genres with increasing popularity over time.

---

## ▶️ Run the Project

```bash id="l0v15x"
# Install dependencies
pip install -r requirements.txt

# Run script (Jupyter / Python)
python analysis.py
```

---

## 📦 Requirements

```txt id="5q04sl"
pandas
seaborn
scipy
matplotlib
```

---

## ⚠️ Limitations

* Dataset is static (not real-time)
* Limited feature engineering
* Basic statistical modeling

---

## 🔮 Future Improvements

* 🤖 Apply machine learning models for prediction
* 📊 Use interactive dashboards (Streamlit / Plotly)
* 🌐 Integrate real-time data sources
* 🧠 Advanced feature engineering


⭐ If you like this project, give it a star!
