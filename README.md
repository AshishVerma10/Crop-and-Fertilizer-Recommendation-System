# 🌾 Smart Harvest – Crop & Fertilizer Recommendation System

An end-to-end Machine Learning web application that recommends the most suitable **crop** and **fertilizer** based on soil nutrients and environmental conditions.

Built using **Scikit-learn, CatBoost, and Streamlit**.

---

## 🚀 Features

- 🌱 Crop Recommendation based on soil and climate parameters
- 🧪 Fertilizer Recommendation for optimal agricultural yield
- 🤖 Multiple ML models with ensemble approach
- 📊 Interactive and user-friendly Streamlit interface
- ⚡ Fast prediction system with pre-trained models
- 📁 Clean and modular project structure

---

## 🧠 Machine Learning Approach

### Crop Recommendation Models
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Bagging Classifier (Ensemble)

### Fertilizer Recommendation Models
- Gaussian Naive Bayes
- CatBoost Classifier
- Ensemble Learning Strategy

Models were trained on agricultural datasets containing soil nutrients and environmental factors.

---

## 📂 Project Structure

```
Crop-and-Fertilizer-Recommendation-System/
│
├── Datasets/
├── Models/
├── Images/
├── catboost_info/
├── app.py
├── Analysis of Datasets.ipynb
├── crop-recommendation.ipynb
├── fertilizer-recommendation.ipynb
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Crop-and-Fertilizer-Recommendation-System.git
cd Crop-and-Fertilizer-Recommendation-System
```

### 2️⃣ Install Required Libraries

```bash
pip install streamlit scikit-learn==1.3.2 numpy==1.24.4 pandas joblib catboost
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## 🧾 Input Parameters

The system takes the following inputs:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Level
- Rainfall
- Soil Type

---

## 📊 Output

- ✅ Recommended Crop
- ✅ Recommended Fertilizer

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- CatBoost
- Streamlit
- Pandas
- NumPy
- Joblib

---

## 🎯 Future Enhancements

- 🌍 Deployment on Streamlit Cloud / AWS
- 📱 Mobile-responsive UI
- 📈 Model accuracy comparison dashboard
- 🌦️ Real-time weather API integration
- 🔄 Automated model retraining pipeline

---

## 👨‍💻 Author

**Ashish Kumar Verma**  
B.Tech – Computer Science & Engineering  
Machine Learning & Data Science Enthusiast  

---

## 📜 License

This project is developed for educational and research purposes.