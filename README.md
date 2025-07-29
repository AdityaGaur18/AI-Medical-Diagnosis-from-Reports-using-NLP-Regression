# AI-Medical-Diagnosis-from-Reports-using-NLP-Regression

# AI Medical Diagnosis from Reports 🧠📄

This project demonstrates how AI can be used to extract relevant patient information (like name and symptoms) from medical reports using OCR and NLP, and predict the most probable disease using regression and classification models.
 

## 📌 Project Objective

To build a smart diagnostic assistant that:
- Extracts patient information and symptoms from scanned or typed medical reports.
- Automatically predicts the disease using trained machine learning models.
- Stores extracted and predicted data into an Excel file for historical tracking.

 
## 🔍 Features

- 🧾 OCR-based data extraction from medical reports (PDF/Image to text)
- 🤖 NLP preprocessing for symptom extraction
- 📊 Machine learning for disease prediction:
  - Linear Regression
  - Decision Tree
  - Random Forest
- 📁 Excel-based record keeping of patient data
- 📈 Evaluation metrics (R² Score, MAE)
- 🧪 Synthetic data generation for model training

 

## 🧠 Model Performance (on synthetic dataset)

| Model           | R² Score | MAE    |
|----------------|----------|--------|
| LinearRegression | 0.88     | 5.68   |
| DecisionTree     | 0.55     | 10.04  |
| RandomForest     | 0.77     | 7.23   |
 

## 🛠️ Technologies Used

- Python
- Jupyter / Google Colab
- Pandas, NumPy
- Scikit-learn
- OpenCV, Pytesseract (for OCR)
- Regular Expressions (re)
- Matplotlib / Seaborn (optional for visualization)


## 📂 Files Included

- `EMD.ipynb` – Complete notebook with OCR, NLP, and ML pipeline
- `disease.csv` – Disease dataset (optional)
- `doctor.csv` – Doctor references (optional)
- `medicine.csv` – Medicines dataset (optional)
- `records.xlsx` – Auto-generated patient record (output)

 
