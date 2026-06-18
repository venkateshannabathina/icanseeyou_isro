# Project Name

A structured data science / machine learning project workflow.

## Directory Structure

```text
├── notebooks/
│   ├── 00_environment_setup.ipynb
│   ├── 01_data_acquisition.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_preprocessing.ipynb
│   ├── 04_bls_detection.ipynb
│   ├── 05_feature_engineering.ipynb
│   ├── 06_validation_models.ipynb
│   └── 07_evaluation.ipynb
│
├── src/
│   ├── ingestion/
│   ├── preprocessing/
│   ├── detection/
│   ├── features/
│   ├── validators/
│   ├── fusion/
│   ├── visualization/
│   └── utils/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── samples/
│
├── reports/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Setup Instructions

1. **Create and Activate a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   # or
   .\venv\Scripts\activate   # On Windows
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Install the source package in editable mode (optional but recommended):**
   ```bash
   pip install -e .
   ```
