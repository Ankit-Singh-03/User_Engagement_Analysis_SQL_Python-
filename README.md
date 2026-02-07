# 🍽️ Yelp Restaurant Success Analysis  
### Understanding the Impact of User Engagement on Restaurant Performance

---

## 📌 Project Overview

This project analyzes Yelp restaurant data to understand how **user engagement metrics** (reviews, tips, check-ins, sentiment, elite users, etc.) influence **business success indicators** like review count and average star ratings.

Using Yelp’s publicly available dataset (JSON format), this study explores correlations, trends, city-level insights, and behavioral patterns that drive restaurant success.

> 🎯 Goal: Identify actionable insights that restaurants can use to improve visibility, customer engagement, and long-term success.

---

## ❓ Problem Statement

In a highly competitive restaurant industry, business success depends on more than food quality alone.

This project investigates:

- Does higher user engagement lead to better ratings?
- Do sentiment metrics like *useful*, *funny*, and *cool* correlate with business success?
- How does engagement vary across cities, ratings, and time?
- Do elite Yelp users significantly impact restaurant performance?

---

## 🎯 Research Objectives

- Quantify correlation between:
  - Reviews
  - Tips
  - Check-ins
  - Ratings
- Analyze sentiment engagement metrics (`useful`, `funny`, `cool`)
- Study engagement trends over time
- Compare high-rated vs low-rated businesses
- Identify geographic performance patterns
- Evaluate the impact of elite users

---

## 📂 Dataset Information

This dataset is a subset of Yelp data covering 8 metropolitan areas in the USA and Canada.

### Files Used:
- `business.json`
- `review.json`
- `user.json`
- `tip.json`
- `checkin.json`

### Dataset Size:
- ~150,000 total businesses
- ~35,000 open restaurant businesses analyzed

All JSON files were loaded into a structured database for efficient querying and analysis.

---

## 🛠️ Tech Stack

- **SQL** – Data extraction & transformation  
- **Python (Pandas, NumPy)** – Data cleaning & analysis  
- **Matplotlib / Seaborn** – Visualization  
- **Statistical Analysis** – Correlation studies  
- **Jupyter Notebook** – Exploratory analysis  

---

## 📊 Key Findings

### 1️⃣ Ratings vs Review Count

- Higher ratings do **not** guarantee higher review counts.
- Review count reflects engagement, not necessarily satisfaction.
- Restaurant success is multi-dimensional.

---

### 2️⃣ Engagement vs Ratings

- Engagement increases steadily from 1-star to 4-star restaurants.
- 4-star restaurants exhibit the highest engagement.
- Slight drop in engagement at 5-star rating (possible niche/saturation effect).

---

### 3️⃣ Correlation Between Reviews, Tips & Check-ins

Strong positive correlation observed between:

- Reviews ↔ Tips  
- Reviews ↔ Check-ins  
- Tips ↔ Check-ins  

Increasing one engagement metric often increases others.

---

### 4️⃣ High-Rated vs Low-Rated Businesses

High-rated restaurants (above 3.5 stars):
- Show consistently higher engagement
- Maintain steady or growing interaction over time

Low-rated restaurants:
- Show weaker and inconsistent engagement patterns

---

### 5️⃣ Geographic Insights

Top Performing Cities:
- 🥇 Philadelphia  
- 🥈 Tampa  
- 🥉 Indianapolis  
- 🏅 Tucson  

These cities demonstrate strong engagement and higher composite success metrics.

---

### 6️⃣ Time Trend Analysis

- Engagement dropped during COVID period
- Successful restaurants maintain long-term engagement stability
- Peak engagement season: **November – March**

---

### 7️⃣ Sentiment Metrics Impact

Yelp sentiment indicators:
- 👍 Useful
- 😂 Funny
- 😎 Cool

Higher counts of these metrics correlate with:
- Greater engagement
- Higher visibility
- Stronger business performance

---

### 8️⃣ Elite Users Impact

- Elite users are fewer but contribute disproportionately to total reviews.
- Positive relationships with elite users can significantly increase exposure and credibility.

---

### 9️⃣ Busiest Hours

Peak engagement time:
🕓 **4 PM – 1 AM**

Business implication:
- Optimize staffing during peak hours
- Run targeted evening promotions

---

## 📈 Business Recommendations

✔ Focus on boosting total engagement (reviews, tips, check-ins)  
✔ Build relationships with elite users  
✔ Encourage high-quality, meaningful reviews  
✔ Optimize operations during peak hours  
✔ Expand in high-performing cities  
✔ Maintain consistent service quality  

---

## 📁 Project Structure
├── data/
├── notebooks/
├── sql/
├── visualizations/
├── README.md
└── Report.pdf

---

## 🎯 Conclusion

Restaurant success is influenced by multiple engagement-driven factors beyond ratings alone.

Consistent user interaction, sentiment strength, elite user involvement, and geographic positioning significantly impact long-term business performance.

This project demonstrates how data analytics can support strategic decision-making in the restaurant industry.

---

## 👤 Author

**Ankit Singh**  
Aspiring Data Analyst  
SQL | Python | Business Analytics  

---

