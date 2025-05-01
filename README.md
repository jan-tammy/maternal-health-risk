# 👩‍⚕️ Maternal Health Risk Classification

This project aims to predict the maternal health risk level (Low, Mid, or High) of pregnant women using clinical data. Leveraging machine learning models, the objective is to assist healthcare providers in early risk assessment and intervention.

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository - Maternal Health Risk Data Set](https://archive.ics.uci.edu/dataset/863/maternal+health+risk)
- **Features:**
  - `Age`: Age in years
  - `SystolicBP`: Systolic blood pressure (mmHg)
  - `DiastolicBP`: Diastolic blood pressure (mmHg)
  - `BS`: Blood sugar levels (mmol/L)
  - `BodyTemp`: Body temperature (°F)
  - `HeartRate`: Heart rate (bpm)
  - `RiskLevel`: Target variable – risk level during pregnancy (`low`, `mid`, `high`)

## 🔍 Project Workflow

1. Data Exploration and Cleaning
2. Feature Scaling and Encoding
3. Model Building using:
   - Logistic Regression
   - K-Nearest Neighbors
   - Random Forest
   - Gradient Boosting
4. Model Evaluation using:
   - Confusion Matrix
   - Classification Report
   - Accuracy Score
5. Comparison of Model Performance

## ✅ Results

- The **best-performing model** was: `Random Forest`
- It showed the highest accuracy and generalization across all classes.

## 🛠️ Tech Stack

- Python 3.12
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `ucimlrepo` (for data loading)

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/maternal-health-risk.git
   cd maternal-health-risk
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter notebook:

   ```bash
   jupyter notebook "Maternal Risk Classification.ipynb"
   ```

## 📌 Future Enhancements
- Add interactive web dashboard using Streamlit
- Incorporate SHAP values for feature interpretability
- Apply cross-validation and hyperparameter tuning
- Deploy as a web app for real-world use

## 👤 Author
Janhavi Tamhankar  
MS in Statistics and Data Science  
University of Texas at Dallas  
[LinkedIn](https://www.linkedin.com/in/janhavitamhankar/)
