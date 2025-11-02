# 🧠 Employee Performance Prediction  
> Because even machines can help HR spot who needs a break (or a raise). ☕💼  
  

---

## 🌸 Project Overview  

This project is a **Machine Learning classification model** that predicts how an employee is performing —  
`Low`, `Average`, or `High` — based on their work patterns, satisfaction, and experience.  

Basically, it’s like giving HR a little AI-powered crystal ball 🔮  

---

## 🚀 Why I Built This  

To practice:
- End-to-end ML pipeline building  
- Data creation, cleaning, encoding, feature engineering  
- Multi-class classification using **Logistic Regression**  
- Visual storytelling with **Seaborn** & **Matplotlib**  
- And… making a boring HR dataset actually fun ✨  

---

## 🧩 Tech Stack  

| Category | Tools Used |
|-----------|-------------|
| Language | Python 🐍 |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-learn (Logistic Regression) |
| Deployment Ready | Joblib |
| Version Control | GitHub Desktop 🖥️ |

---

## 📊 Project Workflow  

1. **Problem Understanding**  
   Define the goal → Predict employee performance for better workforce insights.  

2. **Data Creation**  
   Synthetic dataset of 1000 employees generated with NumPy.  
   Features include:  
   - `Age`, `Department`, `ExperienceYears`  
   - `HoursWorkedPerWeek`, `SatisfactionLevel`  
   - `ProjectsCompleted`, `LastPromotionYears`

3. **Data Analysis**  
   - Summary stats with `.describe()` and `.info()`  
   - Null and duplicate check ✅  
   - Histograms and countplots for visual story  

4. **Feature Engineering**  
   Added smart derived features:
   - `ExperienceCategory` → Junior / Mid / Senior  
   - `Overworked` → Binary flag if >50 hours/week  
   Encoded and scaled everything for the ML model.  

5. **Model Training**  
   - Algorithm: Logistic Regression (`multi_class='ovr'`)  
   - Target: Employee performance (3 classes)  
   - Evaluation: Accuracy, F1-score, Precision, Recall  

6. **Results**  
   💥 Model Accuracy: Around **80–85%** (varies slightly per run)  
   🧾 Saved model → `employee_performance_model.pkl`  

---

## 🪄 Prediction Example  

```python
Prediction for new employee: Average



🌷 Future Goals

Add Random Forest for better interpretability 🌲

Deploy on Streamlit or FastAPI for an HR dashboard 🖥️

Add SHAP/LIME visual explanations

Automate retraining on new HR data


Fun Fact

If an employee works 55 hours a week and still smiles — they either love their job or are on caffeine level 3000 ☕🔥

👩‍💻 Author

Sudeshna
Data Enthusiast | Azure Background | Learning ML, One Model at a Time
