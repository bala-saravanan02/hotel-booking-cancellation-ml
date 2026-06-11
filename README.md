# 🏨 Hotel Booking Cancellation Predictor

![Accuracy](https://img.shields.io/badge/Accuracy-88.15%25-brightgreen?style=flat-square)
![ROC--AUC](https://img.shields.io/badge/ROC--AUC-0.9538-brightgreen?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-orange?style=flat-square)

An end-to-end ML project on real hotel booking data from Portugal — predicting which guests will cancel before they do.

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 88.15% |
| ROC-AUC | 0.9538 |
| F1 (Canceled class) | 0.84 |

---

## 💡 Key Insights

- **Non-refundable deposits** paradoxically drive nearly 100% cancellation rate
- **Longer lead times** = higher cancellation risk (+0.29 correlation)
- **Parking requests** = near-zero cancellation risk (guests who plan to drive, show up)
- **Special requests** anchor guest commitment — more requests, fewer cancellations

---

## 🛠️ Tech Stack
`Python` · `Pandas` · `Seaborn` · `XGBoost` · `Scikit-learn` · `Category Encoders`

---

## 📁 Dataset
[Hotel Booking Demand — Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

---

*Built by [Bala Saravanan](https://github.com/bala-saravanan02) as part of an AI/ML portfolio.*
