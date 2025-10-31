# t20-world-cup-ml-project


---

# 🏏 T20 World Cup Machine Learning Project

### Predicting Player Total Runs Using Regression Models

This project aims to predict **Total Runs** scored by T20 World Cup players using match-level features such as **Matches Played (Mat)** and **Innings Batted (Inns)**.
The project involves data cleaning, exploratory analysis, model building, and performance comparison using multiple machine learning algorithms.

---

## 📁 Project Structure

```
├── t20-stats.csv
├── T20_World_Cup_Prediction.ipynb
├── README.md
└── images/
```

---

## ✅ Project Objectives

* Clean and preprocess the T20 World Cup dataset
* Analyze batting performance metrics
* Build regression models to predict total runs
* Compare models using RMSE and MAPE
* Identify the most reliable and accurate model

---

## 🔍 Dataset Description

The dataset includes:

* **Mat** – Matches played
* **Inns** – Innings batted
* **Runs** – Total runs scored

Additional computed metrics and visuals are included in the notebook.

---

## 🧠 Machine Learning Models Used

The following regression models were implemented and compared:

| Model                       | Description                          |
| --------------------------- | ------------------------------------ |
| **Linear Regression**       | Baseline model                       |
| **Decision Tree Regressor** | Rule-based nonlinear model           |
| **Random Forest / Bagging** | Ensemble tree-based method           |
| **Voting Regressor**        | Aggregated ensemble                  |
| **Stacking Regressor**      | Meta-model combining multiple models |

---

## 📊 Key Steps Performed

✅ Data cleaning and transformation
✅ Exploratory Data Analysis (EDA)
✅ Feature selection (Mat, Inns)
✅ Model training and evaluation
✅ Error metrics comparison
✅ Visualization of results

---

## 📈 Model Performance Summary

| Model                   | RMSE                        | MAPE                           |
| ----------------------- | --------------------------- | ------------------------------ |
| Decision Tree           | High RMSE but lowest MAPE   | ✔ Lowest proportional error    |
| Random Forest (Bagging) | Moderate RMSE               | –                              |
| Voting Regressor        | Not best                    | –                              |
| **Stacking Regressor**  | **✅ Lowest RMSE (~176.67)** | Most stable & consistent model |

---

## 🏆 Final Conclusion

* **Decision Tree Regressor** had the best **MAPE** (0.278), meaning it predicted proportions well.
* But due to high RMSE, it was not the most stable model.
* ✅ **The Stacking Regressor performed best overall** with the **lowest RMSE**, making it the recommended model for this task.

---

## 🛠 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib

---

## 📂 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/t20-world-cup-ml.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook T20_World_Cup_Prediction.ipynb
```

---



---

## 📬 Contact

If you’d like to discuss this project or collaborate:
**LinkedIn:** (http://linkedin.com/in/sehanahmed)
**Email:** (sehanahmed17@gmail.com)

---


