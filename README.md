# 🏠 House Price Prediction using Machine Learning

This project predicts house sale prices based on various features using a supervised machine learning approach. It serves as a beginner-to-intermediate level ML regression task using Python and scikit-learn.

---

## 📁 Dataset

The dataset used is from a typical housing dataset (similar to the Ames Housing Dataset). It includes:
- Numerical features (e.g., `GrLivArea`, `BedroomAbvGr`, `FullBath`)
- Categorical features (e.g., `MSZoning`, `Neighborhood`, `HouseStyle`)

---

## 🎯 Objective

To build a regression model that predicts house sale prices accurately using engineered features from both numerical and categorical data.

---

## 🧠 ML Model Used

- **Linear Regression**: A baseline model to predict continuous output (`SalePrice`).

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas, NumPy** – data manipulation  
- **Matplotlib, Seaborn** – EDA & visualization  
- **Scikit-learn** – modeling, preprocessing, and evaluation  
- **Jupyter Notebook** – development environment

---

## 🔄 Workflow

1. **Data Loading** – Reading CSV using `pandas.read_csv`
2. **EDA** – Shape, null values, feature types, correlations
3. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables (Label Encoding)
   - Feature selection
4. **Model Training** – Using `LinearRegression`
5. **Model Evaluation**
   - MSE (Mean Squared Error)
   - RMSE (Root Mean Squared Error)
   - R² Score
6. **Visualization**
   - Actual vs Predicted Price plot

---

## 📈 Evaluation Metrics

| Metric | Value (Example) |
|--------|-----------------|
| MSE    | ~3.2e+09        |
| RMSE   | ~56,000         |
| R²     | ~0.85           |

---

## 📊 Results

- Achieved an R² score of approximately 0.85 using Linear Regression.
- Categorical variables were encoded using `LabelEncoder`.
- Strong correlation between `GrLivArea` and `SalePrice`.

---

## 📷 Sample Visualizations

- Heatmap of correlations
- Distribution plot of `SalePrice`
- Scatter plot of Actual vs Predicted prices

---

## 🚀 Future Improvements

- Try advanced models like **Random Forest**, **XGBoost**, or **LightGBM**
- Feature importance analysis
- Hyperparameter tuning
- Web deployment using **Streamlit** or **Flask**

---

## 🧑‍💻 Author

**Krrish Yaduka**  
Contact: LinkedIn: https://www.linkedin.com/in/krrish-yaduka-16aa72293/
Feel free to connect and discuss improvements or collaborations.

---

## 📄 License

This project is licensed for educational purposes.

