# Malicious-URLs-ML-Project

## 1. Project structure

```
Malicious-URLs-ML-Project/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   └── urls_original.csv       (dataset downloaded from kaggle)
│
├── notebooks/
│   └── models.ipynb                (final submission file with preprocessing and models)
│
```

## 2. Dataset

We use the **Malicious URLs Dataset** from Kaggle.

**Download Link:** *(https://www.kaggle.com/datasets/siddharthkumar25/malicious-and-benign-urls)*

After downloading, place the file into: Malicious-URLs-ML-Project\data\raw

> Note: The raw dataset is not modified.  
> All transformations occur in `models.ipynb`

## 3. Setup Instructions

### 1. Create Python environment (optional)
```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```

## 3. How to Run Project

### 1. Preprocessing

Open and run: `models.ipynb`

This notebook will:
-Load the raw dataset
-Clean and preprocess the URLs
-Extract lexical/structural features
-Split the dataset into classes used for training and testing.
-Address class imbalance and scaling
-Train and evaluate the models
-Output graphs and charts for visualization
