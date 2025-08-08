# 🎬 IMDb Data Exploration

## 📚 Project Overview

This project explores the IMDb dataset containing the **1,000 most popular movies** from 2006 to 2016, with detailed metadata including titles, genres, directors, cast, revenues, ratings, and more. The goal is to uncover patterns and insights around popularity, revenue drivers, and film characteristics.

## 📊 Dataset Summary

- **Source:** [Kaggle – IMDB Data from 2006 to 2016 (PromptCloudHQ)](https://www.kaggle.com/datasets/PromptCloudHQ/imdb-data)  
- **Entries:** 1,000 movies  
- **Columns Include:**  
  - `Rank`, `Title`, `Genre`, `Description`, `Director`, `Actors`, `Year`  
  - `Runtime (Minutes)`, `Rating`, `Votes`, `Revenue (Millions)`, `Metascore`

## 🔍 Key Findings

- 🎥 There are about **277 action movies** in the dataset.  
- 📅 The year **2006** had the highest average voting rating at approximately **7.14**.  
- 💰 **2009** recorded the highest average movie revenue.  
- 📈 The correlation between movie **rating and revenue** is about **0.217**, suggesting rating has little to no effect on revenue.  
- 🎬 The top 5 directors with the highest average ratings are:  
  1. Aamir Khan — 8.50  
  2. Abdellatif Kechiche — 7.80  
  3. Adam McKay — 7.00  
  4. Adam Shankman — 6.30  
  5. Adam Wingard — 5.90  
- ⏳ The longest movies (runtime > 175 minutes) include:  
  - *The Hateful Eight*  
  - *The Wolf of Wall Street*  
  - *La Vie d'Adèle*  
- 💵 The highest-grossing movie was *The Force Awakens*, making nearly **$1 billion USD**.  
  - *Avatar* is second with about **$760 million USD**.  
  - *Jurassic Park* is third, with approximately **$652 million USD**.  
- 📊 Movies were classified by rating into tiers:  
  - **Excellent:** rating > 7.9  
  - **Good:** rating between 6.0 and 7.9  
  - **Average:** rating ≤ 5.9  
- Most movies fall into the **Good** category.  
- 📉 The lowest-rated movie was *Disaster Movie* (rating 1.9), a comedy.  
- ⭐ The highest-rated movie was *The Dark Knight* with a rating of 9.0, an action crime drama.

## 🌱 Insights & Suggestions

- Ratings do not strongly predict revenue, implying other factors like marketing and franchise strength are more influential.  
- Directors with higher average ratings might be studied for storytelling or style patterns.  
- Runtime doesn’t necessarily affect revenue or rating but very long films may be blockbusters or epics.  
- Rating-based classification can guide marketing and recommendation strategies.

## 🚀 How to Use This Project

### Prerequisites

- 🐍 Python 3.7+  
- 📓 Jupyter Notebook or any Python IDE  
- 📦 Libraries: pandas, matplotlib, seaborn  

### Installation

```bash
git clone https://github.com/zackahbl1/imdb-data-exploration.git
cd imdb-data-exploration
pip install -r requirements.txt
jupyter notebook "IMDb Data Exploration.ipynb"
