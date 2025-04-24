## 🚗 Tesla Stock Price Prediction with Feature Engineering and Grid Search CV

### 🔍 Overview
Developed a machine learning model to predict **Tesla's stock prices** using historical data. The workflow includes extensive **feature engineering** and model optimization using **GridSearchCV** to select the best-performing regression model.

---

### ⚙️ Key Highlights

- 📈 **Data**: Historical stock data for Tesla (TSLA)
- 🧠 **Feature Engineering**:
  - Created lag features (e.g., previous day prices)
  - Calculated technical indicators (moving averages, returns, etc.)
- 🤖 **Model Selection**:
  - Used multiple regression algorithms (e.g., Linear, Ridge, Lasso)
  - Applied **GridSearchCV** with cross-validation to find optimal hyperparameters
- 📊 **Evaluation Metrics**:
  - RMSE (Root Mean Squared Error)
  - R² Score
  - Cross-validation mean score

---

### 🛠 Tech Stack

- `Python`
- `Pandas` for data manipulation
- `NumPy` for numerical operations
- `Scikit-learn` for machine learning and model selection
- `Matplotlib` / `Seaborn` for visualization

---

### ✅ Result
The final model provides a robust estimate of Tesla’s closing prices, validated through cross-validation and tested on unseen data.

