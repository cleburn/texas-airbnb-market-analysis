# 🏡 Texas Airbnb Market Analysis – Austin Edition

Exploratory Data Analysis (EDA) of Airbnb listings in Austin, Texas.  
This project applies **Matplotlib**, **Seaborn**, and **Probability** concepts to uncover data-driven insights into short-term rental pricing and neighborhood dynamics.

---

## 📊 Project Overview

This analysis explores how Airbnb listing attributes — such as **price**, **review score**, and **availability** — relate to one another and shape the Austin rental market.

**Core Questions**
1. Which neighborhoods have the highest median nightly prices?  
2. What does the distribution of prices look like across Austin?  
3. How do availability and reviews correlate with price?  
4. How do outliers influence the perception of the “average” listing price?

---

## 🧰 Tech Stack

- Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy  
- Jupyter Notebook · VS Code · GitHub

---

## 📂 Structure

```
texas-airbnb-market-analysis/
├── notebooks/
│   └── austin_airbnb_eda.ipynb
├── visuals/
│   ├── price_vs_review_scores.png
│   ├── availability_vs_price.png
│   └── price_distribution_CI_filtered.png
└── README.md
```

---

## 🧮 Dataset

Source: [Inside Airbnb – Austin](http://insideairbnb.com/get-the-data/)  
`listings.csv` contains metadata for thousands of short-term rentals across Austin, Texas.

---

## 🧠 Key Findings

### Price vs Rating  
No strong linear relationship. High-rated listings appear across all price ranges, showing that excellent reviews are not limited to premium properties.

### Availability vs Price  
A mild negative trend suggests that more expensive listings are booked fewer days per year — consistent with premium pricing and niche demand.

### Distribution & Probability  
- The **mean nightly rate** across all listings was ≈ **$283**, inflated by extreme luxury listings (up to $50 000 per night).  
- After filtering to listings **≤ $1 000**, the mean stabilized at ≈ **$184**, closely matching the **median ($132)**.  
- The **95 % confidence interval** for the typical mean price ranged from **$246 – $320** before filtering, then narrowed after removing outliers.  
- **Median** and **trimmed mean** proved more reliable indicators of true market behavior than the raw mean.

### Market Insight  
Austin’s Airbnb market shows a healthy mid-range cluster around $150 – $200 per night, with a small number of ultra-luxury properties creating a heavy right-skew.  
Filtering or trimming outliers reveals a clearer and more representative view of the city’s typical nightly pricing.

---

## 🎯 Objective

Build foundational skill in:
- Data cleaning and transformation with **Pandas**
- Visualization with **Matplotlib** and **Seaborn**
- Probability and confidence-interval estimation
- Clear, plain-language communication of data insights

---

## ✅ Week 3 Deliverables

- Added scatterplots for **price vs review_scores_rating** and **availability vs price**  
- Conducted **probability & confidence-interval** analysis for nightly prices  
- Demonstrated the impact of **outliers** on averages and variance  
- Saved final figures (screen-optimized, 7 × 4 in @ 150 dpi) to `/visuals/`  
- Completed full markdown commentary and polished notebook conclusions

---