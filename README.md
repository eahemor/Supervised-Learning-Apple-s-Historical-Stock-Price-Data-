# Supervised-Learning-Apple-s-Historical-Stock-Price-Data

This project applies five supervised regression models (Linear Regression, Ridge, Lasso, ElasticNet, and Random Forest) to forecast Apple's historical stock prices using daily data from 1980 to 2023.

## 📊 Dataset

- Source:f = pd.read_csv("Apple historical_data.csv")
- Features: Open, High, Low
- Target: Close

## 🔧 Preprocessing Steps

- Checked for missing values and outliers
- Scaled data using MinMaxScaler
- Split into 80% training, 20% test

## 🧠 Models Used

- Multiple Linear Regression
- Polynomial Regression
- Support Vector Regression (SVR)
- Decision Tree Regressor
- Random Forest Regressor

## 🖼 Visuals and code

Find model results and plots in the `/screenshots/` folder.

## 🧮 Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 📁 Files

- `Apple_Stock_Prediction_Code.py`: (N/A)
- `screenshots/`: Markdown report visuals (text, code blocks, and output)
- `data/`: Cleaned CSV (N/A)

## 📝 Conclusion

Random Forest provided the best balance between performance and generalization. SVR showed solid results on recent price fluctuations. All models scored high R² values.

---
Data Science Project
Ebenezer Ahemor

