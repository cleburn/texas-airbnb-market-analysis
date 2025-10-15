# 🏡 Texas Airbnb Market Analysis – Austin Edition

Exploratory Data Analysis (EDA) of Airbnb listings in Austin, Texas.  
This project applies **Matplotlib**, **Seaborn**, and **Probability** concepts to uncover data-driven insights into short-term rental pricing and neighborhood dynamics.

---

## 🎯 Objective

Develop data visualization and probability intuition through real-world analysis of Airbnb market data.

**Core Questions**
1. Which neighborhoods have the highest median nightly prices?
2. What does the distribution of prices look like across Austin?
3. How do availability and reviews correlate with price?

---

## 🧰 Tech Stack

- Python · Pandas · NumPy · Matplotlib · Seaborn  
- Jupyter Notebook · GitHub  

---

## 📂 Structure

```
texas-airbnb-market-analysis/
├── data/
│   ├── raw/ → listings.csv (from Inside Airbnb)
│   └── processed/
├── notebooks/
│   └── austin_airbnb_eda.ipynb
├── visuals/
└── README.md
```

---

## 🧮 Dataset

Source: [Inside Airbnb – Austin](http://insideairbnb.com/get-the-data/)  
`listings.csv` contains metadata for thousands of short-term rentals in the Austin area.

---

## 🧠 Insights (to be updated as analysis progresses)

- Median prices differ significantly between neighborhoods.
- Price distribution exhibits right skew (long tail of premium properties).
- Sampling distributions stabilize quickly, illustrating the law of large numbers.

---

## 🪜 Next Steps
- Add scatterplots: `price vs review_scores_rating`, `availability_365 vs price`
- Include probability commentary (expected nightly rate, confidence interval)
- Save key figures to `/visuals`
- Polish notebook + push to GitHub