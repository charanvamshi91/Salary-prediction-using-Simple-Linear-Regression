# 💼 Salary Prediction App using Simple Linear Regression

This is a simple yet powerful machine learning project that predicts a person’s salary based on their years of experience using a **Simple Linear Regression** model. It includes a **Streamlit-based web app** that allows users to make real-time predictions, and is fully deployed on the cloud using **Render**.

---

## 🌐 Live Demo

👉 [Click here to try the app](https://salary-prediction-using-simple-linear-ntan.onrender.com/)

---

## 📌 Project Overview

- 🔢 **Problem Type:** Supervised Regression  
- 📈 **Model Used:** Simple Linear Regression  
- 💡 **Input:** Years of Experience  
- 💰 **Output:** Predicted Salary  
- 💻 **Interface:** Streamlit Web App  
- ☁️ **Deployment:** Render Cloud  

---

## 🧠 Tech Stack

- Python 3  
- Pandas, NumPy  
- Scikit-learn (LinearRegression)  
- Matplotlib (for visualization)  
- Pickle (for saving the model)  
- Streamlit (for interactive UI)  
- Render (for cloud deployment)  

---

## 📂 Project Structure

```
Salary-Prediction-Streamlit/
├── app.py                        # Streamlit web app
├── linear_regression_model.pkl   # Trained regression model
├── requirements.txt              # Python dependencies
├── render.yaml                   # Render deployment config
└── README.md                     # This file
```

---

## 📊 Dataset Overview

- 📁 `Salary_Data.csv` (used during training, not needed in the app)  
- **Columns:**
  - `YearsExperience`: Number of years worked  
  - `Salary`: Annual salary in INR/USD  

---

## 🧪 Model Training Summary

- Used `scikit-learn`'s `LinearRegression` model  
- Trained on 80% of the data and tested on 20%  
- Achieved high R² scores on both train and test sets  
- Saved using `pickle` as `linear_regression_model.pkl`  

---

## 🖥️ How to Run the App Locally

### 🔧 Step 1: Clone the Repository

```bash
git clone https://github.com/charanvamshi91/Salary-prediction-using-Simple-Linear-Regression.git
cd Salary-prediction-using-Simple-Linear-Regression
```

### 📦 Step 2: Install Required Libraries

```bash
pip install -r requirements.txt
```

### 🚀 Step 3: Launch the App

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 🟢 Example Prediction

> **Input:** 5.0 years of experience  
> **Output:** 💰 Predicted Salary: `~₹73,000`

---

## 🌍 Deployment on Render

This app is deployed on [Render](https://render.com), a free cloud hosting platform.

### Deployment Files:
- `requirements.txt`: Lists Python libraries
- `render.yaml`: Tells Render how to run the app

### Deployment Steps:
1. Uploaded project to GitHub  
2. Connected repo to Render  
3. Used the following Start Command:
   ```bash
   streamlit run app.py --server.port 10000
   ```
4. Done! The app auto-builds and runs in the cloud.

---

## 🧾 License

This project is licensed under the [MIT License](https://github.com/charanvamshi91/Salary-prediction-using-Simple-Linear-Regression/blob/main/LICENSE)

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

---

## 🙋‍♂️ Author

**Charan Vamshi**  
🎓 Computer Science Student | 📊 Data Science Enthusiast  
🔗 GitHub: [@charanvamshi91](https://github.com/charanvamshi91)  
🔗 Live App: [Salary Prediction App](https://salary-prediction-using-simple-linear-ntan.onrender.com/)

---

## ⭐ Like This Project?

Give this repo a ⭐ if you found it helpful — it helps others discover it too!
