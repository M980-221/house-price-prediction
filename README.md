# 🏠 House Price Prediction (Machine Learning)

A beginner-friendly **Machine Learning project** that predicts house prices using:
- Size (sqm)
- Rooms
- House age
- Distance to city center

This repo is designed to look professional on GitHub and is easy to extend with a real dataset later.

---

## 📁 Project Structure

```
house-price-prediction/
├── data/
│   └── housing.csv
├── notebook/
│   └── analysis.ipynb
├── src/
│   └── model.py
├── requirements.txt
└── README.md
```

---

## ✅ How to Run

**1) Install dependencies**
```bash
pip install -r requirements.txt
```

**2) Train + evaluate the model**
```bash
python src/model.py
```

You will see evaluation metrics (MAE, RMSE, R²) and a sample prediction.

---

## Dataset

The dataset is in `data/housing.csv` with columns:

- `size_sqm`
- `rooms`
- `age_years`
- `distance_km`
- `price_k` (target)

*(Current dataset is synthetic, created for learning. Replace it with any real housing dataset and keep the same column names.)*

---

## Next Improvements (Optional)

- Add more features (location, bathrooms, parking, etc.)
- Try stronger models (RandomForest, XGBoost)
- Add cross-validation
- Deploy as a simple web app (Streamlit)

---

##  Author

Mohammed — Data Science & Business student
