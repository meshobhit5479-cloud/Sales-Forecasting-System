# 📈 Sales Forecasting System

A Machine Learning-based Sales Forecasting System that predicts future sales using historical sales data. This project uses **Random Forest Regression** and provides an interactive **Streamlit dashboard** for making sales predictions.

---

## 📌 Project Overview

The Sales Forecasting System helps estimate future sales based on factors such as:

- Store ID
- Item ID
- Year
- Month
- Day
- Day of Week

The project performs data preprocessing, feature engineering, visualization, model training, and prediction using machine learning.

---

## 🚀 Features

- 📊 Automatic sales dataset generation
- 🧹 Data preprocessing
- 🔧 Feature engineering
- 📈 Sales trend visualization
- 🤖 Random Forest Regression model
- 📉 Model evaluation (MAE, MSE, RMSE, R²)
- 💾 Model saving using Joblib
- 🌐 Interactive Streamlit web application
- 🔮 Future sales prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Streamlit

---

## 📂 Project Structure

```
Sales-Forecasting-System/
│
├── data/
│   ├── sales_data.csv
│   ├── processed_sales_data.csv
│   ├── X.csv
│   └── y.csv
│
├── graphs/
│   ├── daily_sales_trend.png
│   ├── monthly_sales.png
│   ├── store_sales.png
│   └── item_sales.png
│
├── models/
│   └── sales_model.pkl
│
├── notebooks/
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── visualization.py
│   ├── train_model.py
│   └── predict.py
│
├── app.py
├── generate_dataset.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Sales-Forecasting-System.git
```

Go to the project directory:

```bash
cd Sales-Forecasting-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Launch the Streamlit dashboard:

```bash
python -m streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 📊 Model Information

**Machine Learning Algorithm**

- Random Forest Regressor

**Evaluation Metrics**

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Visualizations

The project generates:

- Daily Sales Trend
- Monthly Sales
- Store-wise Sales
- Item-wise Sales

These charts are automatically saved inside the **graphs/** folder.

---

## 🔮 Prediction

Users can enter:

- Store ID
- Item ID
- Year
- Month
- Day
- Day of Week

The trained model predicts the expected sales instantly through the Streamlit dashboard.

---

## 📸 Screenshots

You can add screenshots here after uploading them.

Example:

```
screenshots/dashboard.png
screenshots/prediction.png
```

---

## 📌 Future Improvements

- Deploy the application online
- Interactive Plotly charts
- Multiple ML model comparison
- Sales forecasting for multiple future dates
- CSV report download
- User authentication

---

## 👨‍💻 Author

**Shivam Yadav**

B.Tech Computer Science & Engineering

---

## ⭐ If you like this project

Please give this repository a ⭐ on GitHub.
