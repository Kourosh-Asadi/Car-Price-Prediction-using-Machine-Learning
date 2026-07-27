# 🚗 Bama Car Price Prediction using Machine Learning

A complete end-to-end Machine Learning project for predicting used car prices in Iran using data collected from **Bama.ir**.

The project includes web scraping, data preprocessing, feature engineering, exploratory data analysis, and comparison of multiple regression algorithms.

---

## 📌 Project Overview

This project automatically collects thousands of used car advertisements from **Bama.ir**, cleans the raw data, extracts useful features, and trains several machine learning models to estimate vehicle prices.

The complete workflow consists of:

- Web Scraping
- Data Cleaning
- Feature Engineering
- Model Training
- Model Evaluation

---

## 📊 Dataset

The dataset was collected directly from **Bama.ir** using Python.

### Dataset Statistics

- **28,000+ advertisements scraped**
- **18,000+ cleaned records**
- Duplicate advertisements removed
- Negotiable prices removed
- Invalid prices filtered
- Missing values handled

### Extracted Features

| Feature | Description |
|---------|-------------|
| Brand | Vehicle brand |
| Year | Production year (Gregorian) |
| Mileage | Vehicle mileage (km) |
| Engine Size | Engine displacement (L) |
| Transmission | Manual / Automatic |
| Body Color | Vehicle color |
| Body Status | Paint condition |
| Price | Target variable |

---

## 🛠 Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Jupyter Notebook

---

## 📈 Machine Learning Models

The following regression algorithms were implemented and compared.

| Model | R² Score |
|--------|---------:|
| Linear Regression | 0.73 |
| Decision Tree | 0.80 |
| Gradient Boosting | 0.80 |
| CatBoost | 0.84 |
| Random Forest | **0.86** |

Random Forest achieved the best performance on the test dataset.


---

## 🔄 Project Pipeline

```
Web Scraping
      │
      ▼
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Machine Learning Models
      │
      ▼
Performance Evaluation
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/bama-car-price-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebooks in order.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 🎯 Future Improvements

- Hyperparameter optimization
- XGBoost implementation
- LightGBM implementation
- Deep Learning models
- Model deployment using Flask/FastAPI
- Real-time price prediction API

---

## 👨‍💻 Author

**Kourosh Asadi**

Email: Kouroshasadi244@gmail.com

Computer Engineering Student

Machine Learning Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!
