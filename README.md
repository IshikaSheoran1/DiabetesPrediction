# DiabetesPrediction
create using colab

# 🩺 Diabetes Prediction Web App

This is a machine learning web app built with **Streamlit** that predicts whether a person is diabetic based on health parameters like glucose level, insulin, BMI, and more.

---

## 📌 Project Description

- 📊 Dataset: [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- 💡 Model: Trained using `RandomForestClassifier` from scikit-learn
- 🧠 Inputs: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
- ⚙️ Deployment: Built using Streamlit and ready to deploy on Streamlit Cloud

---

pip install -r requirements.txt
streamlit run webapp.py

/diabetes-predictor
├── DiabetesPrediction.ipynb     # Jupyter Notebook (model training)
├── trained_model1.sav           # Trained ML model (required)
├── webapp.py                    # Streamlit app code
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
