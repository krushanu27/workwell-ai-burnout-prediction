# WorkWell AI

WorkWell AI is an AI system that predicts employee burnout and productivity risk using workload and behavioral data. It provides decision-support insights through a REST API and an interactive dashboard.

---

## 🔍 Objective

Predict employee burnout risk levels — **Low, Medium, High** — using machine learning, and communicate actionable insights to HR or management with safeguards to prevent misuse.

---

## 🧠 Features

- Data cleaning & preprocessing pipeline
- Exploratory data analysis & feature engineering
- Machine Learning: Random Forest / XGBoost
- Deep Learning: Neural Network
- FastAPI backend for prediction
- Streamlit dashboard for visualization
- Ethical safeguards and access controls

---

## 📁 Project Structure
workwell-ai-burnout-prediction/
├── data/ # Raw and processed datasets
├── notebooks/ # EDA and experimentation notebooks
├── src/ # Core data processing & ML scripts
├── api/ # FastAPI backend
├── dashboard/ # Streamlit dashboard code
├── models/ # Saved ML/DL models
├── docs/ # Architecture diagrams & reports
└── README.md


---

## 🛠️ Tech Stack

- **Programming:** Python  
- **Data Analysis:** NumPy, Pandas  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Deep Learning:** TensorFlow / Keras  
- **Database:** SQLite / PostgreSQL  
- **API:** FastAPI  
- **Dashboard:** Streamlit  
- **Version Control:** Git & GitHub  

---

## 📊 Dataset Description

The dataset consists of structured, non-intrusive attributes such as:
- Working hours
- Overtime frequency
- Task completion rate
- Role and experience level
- Leave history
- Performance trends

Public datasets and ethically generated synthetic data are used to ensure privacy.

---

## 📈 Model Evaluation

Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special emphasis is placed on **recall** to avoid missing high-risk burnout cases.

---

## ⚖️ Ethical Considerations

- The system is **non-diagnostic** and **non-punitive**
- Predictions are advisory and require human interpretation
- No biometric, surveillance, or sensitive personal data is used
- Aggregated insights are preferred over individual-level targeting
- Designed to support wellbeing, not performance enforcement

---

## 🚀 Project Roadmap

- **Weeks 1–2:** Data acquisition, cleaning, EDA  
- **Weeks 3–4:** Feature engineering & ML modeling  
- **Weeks 5–6:** Deep learning & bias review  
- **Weeks 7–8:** FastAPI backend & Streamlit dashboard  
- **Weeks 9–12:** Testing, documentation, and final submission  

---

## 📌 Status

🚧 **Currently under active development**  
(Start date: **1st January**)

---

## 📬 Maintainer

**Krushanu Bhatt**  
GitHub: https://github.com/krushanu27

---

## 📄 License

This project is intended for academic and learning purposes.
