
# Breast Cancer Diagnosis — Malignant vs Benign (KNN)

Classifying **breast cancer diagnosis** as **malignant** or **benign** using a labeled dataset sourced from **Kaggle / UCI Machine Learning Repository**, implemented in a single Jupyter Notebook with a **K‑Nearest Neighbors (KNN)** classifier. [1](https://github.com/danielewhughes/Breast_Cancer_Diagnosis_Classification)

> **Notebook:** `breast_cancer_diagnosis_prediction.ipynb`  
> **Purpose:** Educational demo for tabular ML classification on a well-known breast cancer dataset (Wisconsin / UCI lineage). [1](https://github.com/danielewhughes/Breast_Cancer_Diagnosis_Classification)

---

## What This Notebook Covers

- **Data loading & cleaning** for the UCI/Kaggle breast cancer dataset (tabular, diagnostic features).
- **Exploratory Data Analysis (EDA)**: basic checks, distributions, and correlations (as applicable).
- **Feature preprocessing** suitable for KNN (scaling/normalization where needed).
- **Modeling with KNN**: training, validation, and evaluation.
- **Metrics & visualization**: accuracy, confusion matrix, and other common classification diagnostics.

## Requirements

This project runs in a standard Python data‑science environment (local Jupyter, VS Code, or a cloud notebook service).

**Suggested packages:**
- Python 3.9+
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn` (optional for plots)
- `jupyter` (if running locally)

## Data 

> The dataset referenced is from Kaggle and originates from the UCI Machine Learning Repository (commonly known as the Wisconsin Breast Cancer dataset family). Follow the data‑loading cell(s) inside the notebook to point to the CSV correctly. If you manage your own copy, store it outside version control (e.g., in a local data/ folder) and update the path in the notebook accordingly.

## Getting Started

### 1) Clone the repo
``` bash
git clone https://github.com/danielewhughes/Breast_Cancer_Diagnosis_Classification.git
cd Breast_Cancer_Diagnosis_Classification
```

### 2) Create a virtual environment
``` bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

### 3) INstall dependencies
``` bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4) Open the notebook
``` bash
jupyter notebook breast_cancer_diagnosis_prediction.ipynb
```
