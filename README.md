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

- ## 📊 Visualizations and Outputs

### 📌 Introduction
![Introduction](screenshots/introduction.png)

### 📚 Libraries Used
![Libraries](screenshots/libraries.png)

### 📈 Data Visualizations
![Visual 1](screenshots/visual1.png)
![Visual 2](screenshots/visual2.png)
![Visual 3](screenshots/visual3.png)
![Visual 4](screenshots/visual4.png)

### 🧠 Model Training & Evaluation
![Random Forest Output](screenshots/visual18.png)
![Visual 15](screenshots/visual15.png)
![Visual 16](screenshots/visual16.png)
![Visual 17](screenshots/visual17.png)

### 📌 Conclusion
![Conclusion](screenshots/conclusion.png)


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

