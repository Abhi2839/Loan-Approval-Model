# 🏦 Loan Prediction Model

This project predicts whether a loan should be approved or not using machine learning. It is based on real-world data and explores multiple financial and demographic features to make accurate predictions.

## 📂 Dataset

- **Source**: Kaggle - [Loan Prediction Dataset]((https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset))
- **Features Used**:
  - Income per annum
  - Loan amount
  - Loan term
  - CIBIL score
  - Education level
  - Employment type (Salaried or Self-employed)

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data handling and manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **Scikit-learn** | Machine learning (Decision Tree Classifier) |
| **Joblib** | Saving the trained model |

---

## 🔄 Project Workflow

### 1. Data Preprocessing
- Removed null and inconsistent values
- Encoded categorical values (e.g., Education, Self-employed)
- Applied **IQR (Interquartile Range)** method to cap outliers

### 2. Exploratory Data Analysis
- Used `boxplots` and `heatmaps` for visual analysis
- Analyzed relationships between features like income, loan term, and CIBIL score

### 3. Feature Selection
- Selected key features using correlation and domain knowledge

### 4. Model Training
- Split the dataset into train/test sets
- Trained a **Decision Tree Classifier**
- Evaluated model accuracy on the test set

### 5. Model Export
- Saved the model using `joblib.dump()` as `loan_model.pkl`

---

## 📌 Notes

- This version **does not include Aadhaar or PAN card verification**
- No UI or deployment tools (like **Streamlit** or **FastAPI**) are used
- Project focuses on backend logic and analysis

Linkedin:https://www.linkedin.com/in/abhey-garg-032b53289/
Model colab file:https://colab.research.google.com/drive/1xoeSnmbQiaF6_e9AD1Zdspk9vZcBwkjt#scrollTo=NIMu9-uXx3yT

---


