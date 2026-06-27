# 🩺 Breast Cancer Prediction using Machine Learning

A Machine Learning project that predicts whether a breast tumor is **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using the **Support Vector Machine (SVM)** algorithm.

The model is trained on the Breast Cancer Wisconsin Diagnostic Dataset and achieves approximately **98–99% accuracy** after feature scaling and preprocessing.

---

## 📌 Features

- Data preprocessing and cleaning
- Feature scaling using StandardScaler
- Classification using Support Vector Machine (SVM)
- High prediction accuracy
- Confusion Matrix
- Classification Report
- Sample prediction for new patient data

---

## 📂 Project Structure

```
Breast-Cancer-Prediction/
│
├── data.csv
├── breast_cancer_prediction.py
├── README.md
└── requirements.txt
```

---
Link :https://colab.research.google.com/drive/1zEJ1KwTaZ1-o5a8-Wg07bEiej54ZDWhF?authuser=1
```

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn

---

## 📊 Dataset

This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

Dataset Information:

- Total Samples: 569
- Features: 30
- Classes:
  - Malignant (M)
  - Benign (B)

The dataset contains measurements computed from digitized images of breast mass cell nuclei.

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction.git
```

Move into the project directory

```bash
cd Breast-Cancer-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python breast_cancer_prediction.py
```

---

## 📈 Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Feature Selection
4. Train-Test Split
5. Feature Scaling
6. Train SVM Model
7. Predict Results
8. Evaluate Model Performance

---

## 📋 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

Typical Accuracy:

```
98% - 99%
```

---

## 📷 Sample Output

```
Accuracy : 98.25%

Confusion Matrix

[[41  1]
 [ 1 71]]

Classification Report

              precision    recall  f1-score   support

Malignant       0.98       0.98      0.98        42
Benign          0.99       0.99      0.99        72

Accuracy                              98%
```

---

## 📌 Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Web Application using Flask or Streamlit
- Model Deployment

---

## 📄 Requirements

```
pandas
scikit-learn
```

or install manually

```bash
pip install pandas scikit-learn
```

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository, improve the project, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sanjay Gandhi**

GitHub: https://github.com/SANJAYGANDHI67
