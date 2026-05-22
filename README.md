# Car_price_prediction
<div align="center">

# 🚗 Car Price Prediction System

### End-to-End Machine Learning Application for Vehicle Resale Value Estimation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Deployed](https://img.shields.io/badge/Deployed-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

### 🚀 [Live Demo](https://car-price-prediction-ti9b.onrender.com) | 📂 [View Code](https://github.com/karthik-vana/car-price-prediction)

**Predict your car's resale value instantly with 97% accuracy!**

</div>

---

## 📌 What This Project Does

Enter your car's details → Get instant predicted resale price → Make informed selling decisions!
```
🚗 Your Car Details        🤖 ML Model              💰 Predicted Price
─────────────────────  →  ─────────────────────  →  ─────────────────────
Showroom Price: 8L         Extra Trees Regressor     Resale Value:
Current Age: 3 years       97.3% Accuracy           ⚡ ₹4.8 Lakhs
Kilometers Driven: 30K     
Fuel Type: Petrol          
Seller Type: Individual    
```

---

## 🎯 Project Overview

A **complete machine learning solution** that predicts used car prices based on vehicle specifications and market conditions. This project helps:

✅ **Car Sellers** - Get fair market value for their vehicle  
✅ **Buyers** - Validate if asking price is reasonable  
✅ **Dealers** - Make data-driven pricing decisions  
✅ **Enthusiasts** - Understand depreciation patterns

---

## 🌟 Key Features

| Feature | Description |
|---------|-------------|
| 🎯 **Accurate Predictions** | 97.3% R² Score with Extra Trees Regressor |
| ⚡ **Instant Results** | Get price predictions in under 1 second |
| 🌐 **Web Interface** | Clean, user-friendly Flask application |
| 📊 **Data-Driven** | Based on real market data and trends |
| ☁️ **Cloud Deployed** | Live on Render - accessible anywhere |
| 🔄 **Complete Pipeline** | EDA → Model Training → Deployment |

---

## 📊 Model Performance Comparison

I trained and evaluated **3 different regression models** to find the best performer:

<div align="center">

| 🤖 Model | 📈 R² Score (Accuracy) | 📉 MAE (Lakhs) | ⚡ Status |
|----------|------------------------|----------------|-----------|
| **Extra Trees Regressor** | **97.3%** | **₹0.49L** | 🏆 **Winner** |
| Random Forest Regressor | 95.9% | ₹0.64L | ✅ Excellent |
| Linear Regression | 84.9% | ₹1.21L | ✅ Good |

</div>

### 📈 Visual Comparison
```
Model Accuracy (R² Score)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Extra Trees     ████████████████████  97.3% 🏆
Random Forest   ███████████████████░  95.9%
Linear Reg      █████████████████░░░  84.9%
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 🔍 Data Analysis & Insights

### Dataset Overview

- **Total Records:** 301 cars
- **Features:** 9 (including target)
- **Target Variable:** Selling Price (in Lakhs)

### 📊 Key Features Used

| Feature | Type | Description |
|---------|------|-------------|
| **Present_Price** | Numerical | Current showroom price (Lakhs) |
| **Kms_Driven** | Numerical | Total kilometers driven |
| **Year** | Numerical | Manufacturing year |
| **Fuel_Type** | Categorical | Petrol/Diesel/CNG |
| **Seller_Type** | Categorical | Dealer/Individual |
| **Transmission** | Categorical | Manual/Automatic |
| **Owner** | Numerical | Number of previous owners |

### 🔎 EDA Insights Discovered

**1. Depreciation Pattern**
- Cars lose ~15-20% value in first year
- Depreciation slows after 5 years
- Present price strongly correlates with selling price

**2. Mileage Impact**
- Higher kilometers driven = Lower resale value
- Critical threshold: ~50,000 km
- Premium cars retain value better

**3. Fuel Type Analysis**
- Diesel cars have better resale value
- Petrol cars depreciate faster
- CNG has lowest resale value

**4. Transmission Effect**
- Automatic transmission adds premium
- Manual transmission more common
- Growing demand for automatic

---


## 🚀 Live Application

### 🌐 Try It Now!

**👉 [https://car-price-prediction-ti9b.onrender.com](https://car-price-prediction-ti9b.onrender.com)**

## 📂 Project Structure
```
car-price-prediction/
│
├── 📁 templates/
│   └── index.html              # Frontend UI (HTML/CSS)
│
├── 📄 app.py                   # Flask backend application
├── 🤖 car_price_model.pkl      # Trained ML model (serialized)
├── 📊 car data.csv             # Training dataset
│
├── 📓 notebooks/
│   ├── EDA.ipynb              # Exploratory Data Analysis
│   └── model_training.ipynb   # Model training & comparison
│
├── 📄 requirements.txt         # Python dependencies
├── 📄 Procfile                 # Render deployment config
├── 📄 README.md                # Project documentation
│
├── .gitignore                  # Git ignore rules
└── LICENSE                     # MIT License
```

---

## 🛠️ Technologies & Tools

<div align="center">

### Core Technologies

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Visualization

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Web & Deployment

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

</div>

### 📦 Complete Requirements
```python
# Machine Learning & Data Science
pandas==2.0.3
numpy==1.24.3
scikit-learn==1.3.0

# Visualization
matplotlib==3.7.2
seaborn==0.12.2

# Web Framework
Flask==2.3.2

# Deployment
gunicorn==21.2.0
```

---

## 🎯 Key Achievements

<div align="center">

| Achievement | Description |
|------------|-------------|
| 🎯 **High Accuracy** | 97.3% R² Score on test data |
| ⚡ **Fast Predictions** | Results in <1 second |
| 🌐 **Live Deployment** | Successfully deployed on Render |
| 📊 **Complete Pipeline** | End-to-end ML workflow |
| 🏆 **Best Model Selected** | Compared 3 algorithms systematically |
| 💼 **Production Ready** | Clean code, error handling, logging |

</div>

---

## 📊 Sample Predictions

### Real-World Examples

| Car Details | Predicted Price | Status |
|-------------|----------------|--------|
| Showroom: 10L, Age: 2 yrs, 20K km | ₹7.8 Lakhs | ✅ High value |
| Showroom: 5L, Age: 6 yrs, 80K km | ₹2.1 Lakhs | ✅ Fair |
| Showroom: 15L, Age: 1 yr, 5K km | ₹13.2 Lakhs | ✅ Excellent |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Dataset Source:** Kaggle Car Price Dataset
- **Inspiration:** Real-world car valuation systems
- **Tools:** Scikit-learn, Flask, Render

---

<div align="center">

## 👨‍💻 Created By

### swarnalatha

**Data Analist Enthusiast | Machine Learning  intern**

*Building practical ML solutions for real-world problems*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/https://github.com/Swarna6656)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/swarna-latha-4732b7238)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](swarna1704@gmail.com)


---

### ⭐ Star this repo if you found it helpful!

### 💼 Open to Data Science & ML opportunities

**Made with ❤️ and Python**



</div>
