# KLH-CSE-2024-2420030519-Explainable-AI-Framework-for-Employee-Attrition-Prediction
# Explainable AI Framework for Employee Attrition Prediction

## Project Overview

This project predicts employee attrition using Machine Learning and explains predictions using Explainable AI techniques. It uses the IBM HR Employee Attrition dataset, an XGBoost classification model, and SHAP explanations to help users understand factors influencing predicted attrition risk.

## Objectives

- Analyze employee data and identify patterns associated with attrition.
- Preprocess employee data for Machine Learning.
- Train and evaluate classification models.
- Predict attrition risk for employee profiles.
- Explain predictions using SHAP and LIME.
- Provide a web interface for entering employee details and viewing results.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn and Imbalanced-learn
- XGBoost
- SHAP and LIME
- Flask and Flask-CORS
- HTML, CSS, and JavaScript
- Matplotlib

## Project Features

- Employee attrition dataset analysis and visualizations.
- Data preprocessing, categorical encoding, and class balancing.
- Model training and evaluation.
- Employee attrition prediction through a web interface.
- SHAP-based feature explanations.
- Model comparison, classification report, confusion matrix, and ROC curve.

## Project Structure

- `backend/` — Flask prediction API.
- `frontend/` — HTML, CSS, and JavaScript interface.
- `data/` — Dataset, data loading, EDA, and preprocessing scripts.
- `src/models/` — Model training scripts.
- `src/evaluation/` — Model evaluation scripts.
- `src/explainability/` — Explainability scripts.
- `results/` — Evaluation metrics, charts, trained models, and explanations.
- `docs/` — Project report, research paper, and presentation.
- `requirements.txt` — Python dependencies.

## Setup Instructions

### 1. Create and activate a virtual environment

On Windows PowerShell, run these commands from the project root:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2. Install dependencies

```powershell
python -m pip install -r requirements.txt
```

### 3. Start the backend

```powershell
python backend/app.py
```

The backend is expected to run at `http://127.0.0.1:5000`.

### 4. Start the frontend

Open a second PowerShell terminal, navigate to the `frontend` directory, and run:

```powershell
python -m http.server 5500
```

Open `http://127.0.0.1:5500` in your browser.

Keep both terminal windows open while using the application.

## Results

The `results/` directory contains model evaluation metrics, a classification report, a confusion matrix, a ROC curve, EDA charts, model comparison results, and SHAP/LIME explanation outputs.

## Limitations

Predictions depend on the training dataset and model performance. They are estimates, not guarantees, and should not be used as the sole basis for employment decisions.

## Conclusion

The project combines Machine Learning with Explainable AI to predict employee attrition and provide interpretable explanations through a web application.
