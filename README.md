# 💻 Laptop Price Prediction ML Project

Predict laptop prices based on hardware specifications using Machine Learning.

## 📌 Overview

This project aims to predict the price of a laptop using various hardware and software specifications such as company, processor, RAM, storage, GPU, screen resolution, operating system, and weight. The project follows a complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and deployment. Laptop price prediction projects commonly use regression models and extensive feature engineering on laptop specifications.
---

## 🚀 Features

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Multiple Regression Models
* Model Evaluation
* Price Prediction System
* Deployment Ready
* Interactive User Interface

---

## 📂 Project Structure

```text
Laptop-Price-Prediction-ML-Project/
│
├── data/
│   └── laptop_data.csv
│
├── notebooks/
│   └── Laptop_Price_Prediction.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── assets/
```

---

## 📊 Dataset

The dataset contains laptop specifications including:

* Company
* Product Name
* Type Name
* RAM
* Weight
* Operating System
* Screen Resolution
* CPU
* GPU
* Storage
* Touchscreen
* IPS Display
* Price

These features are commonly used in laptop price prediction datasets. 

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Streamlit / Flask
* Jupyter Notebook

---

## 🔄 Machine Learning Workflow

### 1. Data Collection

* Load laptop dataset
* Inspect data quality

### 2. Data Preprocessing

* Handle missing values
* Remove duplicates
* Encode categorical features
* Feature extraction

### 3. Exploratory Data Analysis

* Brand-wise price analysis
* RAM vs Price relationship
* Storage impact on pricing
* CPU and GPU analysis

### 4. Feature Engineering

* Screen resolution extraction
* CPU brand extraction
* Storage categorization
* Weight processing

### 5. Model Training

Models that can be tested:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

Random Forest is a commonly used high-performing model in laptop price prediction projects.

### 6. Model Evaluation

Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## 📈 Results

The trained model predicts laptop prices based on user-selected specifications and helps users estimate the market value of laptops before purchasing or selling.

Example Input:

```text
Company: Dell
RAM: 16 GB
CPU: Intel Core i7
Storage: 512 GB SSD
GPU: NVIDIA GTX 1650
Weight: 2.1 kg
```

Predicted Output:

```text
Estimated Price: $950
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Muhammad-Musharraf/Laptop-Price-Prediction-ML-Project.git
```

### Navigate to Project

```bash
cd Laptop-Price-Prediction-ML-Project
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

or

```bash
streamlit run app.py
```

---

## 📸 Screenshots

Add screenshots of:

* Homepage
* Data Analysis Dashboard
* Prediction Interface
* Model Results

---

## 🎯 Future Improvements

* Hyperparameter Tuning
* Deep Learning Models
* Real-Time Price Tracking
* API Development
* Cloud Deployment
* Recommendation System

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 👨‍💻 Author

**Muhammad Musharraf**

* GitHub: [Muhammad Musharraf GitHub](https://github.com/Muhammad-Musharraf?utm_source=chatgpt.com)
* LinkedIn: [Muhammad Musharraf LinkedIn](https://www.linkedin.com/in/muhammad-musharraf-437424327/?utm_source=chatgpt.com)

---

⭐ If you found this project useful, consider giving it a star!

[1]: https://vishrut-b.github.io/ML-Project-Laptop-Price-Prediction/?utm_source=chatgpt.com "Laptop Price Prediction"
[2]: https://github.com/Rishabhrv/Laptop-Price-Predictor?utm_source=chatgpt.com "GitHub - Rishabhrv/Laptop-Price-Predictor: The Laptop Price Predictor is a machine learning project that uses Random Forest algorithm to predict the price of laptops. The project involves extensive data preprocessing, manipulation and feature engineering, and provides a Jupyter notebook for further exploration."
