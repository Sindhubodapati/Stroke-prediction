# 🧠 ML Web App with Flask & React

This project demonstrates how to build an **end-to-end Machine Learning web application** using **Flask (Python)** for the backend and **ReactJS** for the frontend. The workflow includes **Exploratory Data Analysis (EDA)**, **model training**, **backend API creation**, and **frontend integration** for real-time predictions.

## 🚀 Features

- 📊 Exploratory Data Analysis on the dataset
- 🧪 Model training and selection from 3 ML models
- ⚙️ API built using Flask to serve ML predictions
- 💻 Responsive UI built with ReactJS
- 🔗 Frontend-backend integration via REST API
- ✅ Final live demo for full-stack prediction flow


## 🛠 Tech Stack

- **Frontend:** ReactJS, JavaScript, HTML, CSS
- **Backend:** Flask (Python), REST API
- **ML Models:** Scikit-learn (Logistic Regression, Random Forest, etc.)
- **Visualization:** Matplotlib, Seaborn
- **Tools:** VSCode, Postman, npm, Python, pip


## 🧪 Workflow Summary

### 1. 📊 Exploratory Data Analysis (EDA)
- Visualize feature distributions
- Handle missing values, outliers, and correlations

### 2. 🔍 Model Training
- Compare 3 different ML models (e.g., Logistic Regression, Random Forest, SVM)
- Evaluate using accuracy, confusion matrix, etc.
- Select and export the best model using `joblib` or `pickle`

### 3. 🛠 Flask Backend
- Create RESTful API with Flask to serve predictions
- Accept user input via JSON and return prediction result
- Enable CORS for frontend access

### 4. 💻 React Frontend
- Build interactive forms for user input
- Handle API requests/responses
- Display prediction result in real-time


## 📂 Project Structure
```
ML-WebApp/
│
├── backend/
│ ├── app.py # Flask app
│ ├── model.pkl # Trained ML model
│ ├── requirements.txt # Python dependencies
│
├── frontend/
│ ├── src/
│ │ ├── App.js # Main React component
│ │ └── ... # Other components
│ └── package.json # npm dependencies
│
├── data/
│ └── dataset.csv # Input dataset for EDA and training
│
└── README.md # Project documentation
```


## 📦 Installation & Setup

### Backend (Flask)

```
cd backend
pip install -r requirements.txt
python app.py 
```

### Frontend (React)
```
cd frontend
npm install
npm start



