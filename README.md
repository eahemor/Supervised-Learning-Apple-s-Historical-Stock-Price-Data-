# Apple-Stock-Price-Prediction-Supervised-Regression

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

This project applies five supervised regression models (Linear Regression, Ridge, Lasso, ElasticNet, and Random Forest) to forecast Apple's historical stock prices using daily data from 1980 to 2023.

---

## 💾 Installation

To set up the project locally:

```bash
git clone https://github.com/eahemor/Supervised-Learning-Apple-s-Historical-Stock-Price-Data.git
cd Supervised-Learning-Apple-s-Historical-Stock-Price-Data
pip install -r requirements.txt
```

---

## 📊 Dataset

- Source: `pd.read_csv("Apple historical_data.csv")`
- Features: `Open`, `High`, `Low`
- Target: `Close`

---

## 🔧 Preprocessing Steps

- Checked for missing values and outliers
- Scaled data using `MinMaxScaler`
- Split into 80% training, 20% test

---

## 📊 Visualizations and Outputs

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

---

## 🧠 Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- Random Forest Regressor

---

## 🧮 Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📁 Project Structure

```text
📦Supervised-Learning-Apple-s-Historical-Stock-Price-Data
 ┣ 📂screenshots/                # Markdown report visuals (text, code blocks, outputs)
 ┣ 📜requirements.txt            # Dependencies
 ┣ 📜README.md                   # Project overview
 ┣ 📜LICENSE                     # MIT License
 ┗ 📜.gitignore
```

---

## 📝 Conclusion

Random Forest provided the best balance between performance and generalisation. SVR showed solid results on recent price fluctuations. All models scored high R² values.

---

**MSc Data Science Project**

**Ebenezer Ahemor**
