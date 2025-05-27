# 🛍️ Customer Intent Insight: Predicting Online Purchase Behavior

This project analyzes over 12,000 user sessions from an e-commerce platform to uncover behavioral patterns and develop machine learning models to predict whether a user will make a purchase.

---

## 📊 Project Goals

- Understand online customer behavior
- Explore feature impact (visitor type, session timing, bounce/exit rates)
- Build and evaluate models for purchase intent prediction

---

## 🔍 Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)
- 12,330 session records | 17 features | Imbalanced target (15.5% purchase rate)

---

## 🧪 Research Questions

1. Are returning visitors more likely to buy?
2. Does time spent on product pages correlate with purchases?
3. Are conversions higher on weekends?
4. How do bounce/exit rates influence outcomes?

---

## ⚙️ Tools & Techniques

- Python (pandas, seaborn, scikit-learn, XGBoost)
- Chi-square tests, t-tests, correlation heatmaps
- Feature engineering, data balancing
- Model evaluation: F1, ROC-AUC, precision/recall

---

## 🧠 Key Findings

- New visitors showed statistically higher purchase rates (p < 0.001)
- Longer time on product pages led to more conversions
- Weekend visitors converted at a higher rate than weekday traffic
- Lower bounce & exit rates correlated strongly with purchases

---

## 🏆 Best Model

**XGBoost Classifier**  
- F1 Score: 68.86%  
- ROC-AUC: 93.11%  
- Precision: 70.2%  
- Recall: 67.4%

---

## 🧩 Conclusion

These insights help e-commerce businesses optimize website layout, tailor marketing campaigns, and better predict buying behavior using actionable machine learning.
