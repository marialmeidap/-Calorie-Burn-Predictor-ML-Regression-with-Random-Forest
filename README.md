# 🔥 Calorie Burn Predictor — ML Regression with Random Forest

This project presents a machine learning regression model built for the [Kaggle Calorie Prediction Challenge](https://www.kaggle.com/competitions/playground-series-s3e25). It predicts how many calories a person is likely to burn based on biometric and physical activity features like age, weight, duration of exercise, heart rate, and temperature.

## 🚀 Project Overview

- **Model Type:** Random Forest Regressor
- **Tech Stack:** Python, Scikit-Learn, Pandas, NumPy
- **Target Variable:** `Calories`
- **Features Used:** `Gender`, `Age`, `Height`, `Weight`, `Duration`, `Heart_Rate`, `Body_Temp`

## 🧪 Model Performance (Validation)

| Metric | Value |
|--------|--------|
| RMSLE  | 0.0663 |
| RMSE   | 4.04   |
| R²     | 0.9958 |

The model was trained using only 10% of the training data to optimize performance in limited-resource environments such as Kaggle Notebooks or Google Colab.

## 📁 Submission

The final predictions were exported to `submission.csv`, with the required `id` and `Calories` format for Kaggle evaluation.

## 💾 Data Access

Due to the large size of the dataset, both `train.csv` and `test.csv` were uploaded in compressed `.zip` format:
- `train.zip`
- `test.zip`

Make sure to unzip them before running the notebook, or include code to read them directly using `pd.read_csv("train.zip")`.

## 💡 Use Case

This model can be used to build intelligent fitness tools where users input their:
- Age
- Weight
- Gender
- Desired calorie burn

And the system recommends how long or how intensely they need to train to meet their goal. It could power:
- Fitness coaching apps
- Gym mirrors with AI assistants
- Personal trainer dashboards
- Diet tracking platforms

## 📚 Files Included

- `calorie_predictor.ipynb` — Jupyter notebook with full workflow
- `submission.csv` — Final predictions
- `train.zip`, `test.zip` — Compressed datasets
- `README.md` — Project documentation

## 🙋‍♀️ About Me

I’m a Machine Learning Engineer in training with a background in commercial and industrial engineering. This project is part of my personal portfolio to demonstrate real-world problem-solving with AI.

---

**If you liked this project, feel free to ⭐ the repo or connect with me!**
