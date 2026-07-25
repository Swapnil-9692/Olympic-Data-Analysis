# 🏅 Olympic Data Analysis with Machine Learning

An interactive web application built using **Python**, **Streamlit**, and **Machine Learning** to analyse 120 years of Olympic history. The project provides insightful visualisations, medal statistics, athlete analysis, country-wise performance, and a medal prediction feature.

---

## 📌 Features

- 🥇 Medal Tally Analysis
- 🌍 Country-wise Performance Analysis
- 🏃 Athlete-wise Analysis
- 📊 Overall Olympic Statistics
- 📈 Interactive Charts and Visualisations
- 🤖 Machine Learning Medal Prediction
- 🎨 User-friendly Streamlit Interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📂 Dataset

This project uses the **120 Years of Olympic History** dataset available on Kaggle.

Files:
- athlete_events.csv
- noc_regions.csv

---

## 🤖 Machine Learning Model

The project includes a **Random Forest Classifier** to predict the likely winning country based on the selected:

- Sport
- Medal Type

### Model Workflow

1. Data Preprocessing
2. Label Encoding
3. Train-Test Split
4. Random Forest Model Training
5. Prediction

---

## 📊 Project Modules

### Medal Tally
- Country-wise medals
- Year-wise medals

### Overall Analysis
- Participating Nations
- Athletes
- Sports
- Events
- Historical Trends

### Country Analysis
- Medal trends
- Performance over the years

### Athlete Analysis
- Age Distribution
- Height & Weight Analysis
- Top Athletes

### Prediction
- Select Sport
- Select Medal
- Predict the likely winning country

---

## 📁 Project Structure

```
Olympic-Data-Analysis/
│
├── app.py
├── helper.py
├── preprocessor.py
├── requirements.txt
├── README.md
│
├── dataset/
│   ├── athlete_events.csv
│   └── noc_regions.csv
│
├── model/
│   ├── random_forest.pkl
│   └── label_encoder.pkl
│
└── images/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Swapnil-9692/Olympic-Data-Analysis.git
```

Go to the project directory

```bash
cd Olympic-Data-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📸 Screenshots

### Home Page



### Medal Tally


### Country Analysis


### Athlete Analysis

### Prediction Page


---

## 🎯 Future Improvements

- Deep Learning Prediction Model
- Medal Prediction Accuracy Improvement
- Live Olympic Data Integration
- User Authentication
- Dark Mode
- Interactive World Map

---

## 👨‍💻 Author

**Swapnil Jadhav**

- GitHub: https://github.com/Swapnil-9692
- LinkedIn: *(Add your LinkedIn profile)*

---

## ⭐ If you like this project

Please consider giving it a **Star ⭐**.
