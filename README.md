

## 💼 Employee Salary Prediction Using Machine Learning

This project predicts the salary of employees or interns using machine learning techniques based on factors such as education, experience, location, and job role. It aims to assist HR teams in fair, data-driven compensation decisions.

---

### 📌 Table of Contents

* [Project Description](#project-description)
* [Tech Stack](#tech-stack)
* [Setup Instructions](#setup-instructions)
* [Model Workflow](#model-workflow)
* [Results](#results)
* [Screenshots](#screenshots)
* [Future Scope](#future-scope)
* [Author](#author)

---

### 📘 Project Description

Traditional methods of determining intern or employee salaries are manual, subjective, and inefficient.
This project automates salary prediction using regression-based machine learning algorithms to improve accuracy and efficiency in HR practices.

---

### 🧰 Tech Stack

* **Programming Language:** Python
* **Libraries Used:**

  * `pandas`, `numpy` – data handling
  * `matplotlib`, `seaborn` – data visualization
  * `scikit-learn` – ML modeling
  * `joblib` – model saving
  * `streamlit` (optional) – web UI for prediction

---

### ⚙️ Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/employee-salary-prediction.git
   cd employee-salary-prediction
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate (Windows)
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook or Streamlit app:**

   ```bash
   jupyter notebook employe-salary-prediction-using-ml.ipynb
   # OR
   streamlit run app.py
   ```

---

### 🔁 Model Workflow

1. Load and explore dataset
2. Clean and preprocess data
3. Perform exploratory data analysis (EDA)
4. Encode categorical variables
5. Train regression models (e.g., Linear Regression, Random Forest)
6. Evaluate model performance using R², MAE, RMSE
7. Save the model
8. (Optional) Deploy using Streamlit

---

### 📊 Results

* **Best Model:** Random Forest Regressor (example)
* **Accuracy (R²):** \~0.87 (can be adjusted based on your results)
* **MAE:** \~2000
* **RMSE:** \~3000
* Predictions align well with real salary trends based on features.

