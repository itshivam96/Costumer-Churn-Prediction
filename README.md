# 🧠 Customer Churn Prediction

Predicting customer churn using machine learning to help businesses retain valuable customers and reduce attrition.

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Dataset](#-dataset)
- [Project Architecture](#-project-architecture)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Future Work](#-future-work)
- [Contributing](#-contributing)
- [License](#-license)

## 📖 Overview

Customer churn prediction is a critical task for businesses aiming to retain customers and improve profitability. This project uses machine learning techniques to analyze customer behavior and predict the likelihood of churn.
<img width="343" height="203" alt="download" src="https://github.com/user-attachments/assets/df88b66f-1313-48b1-8416-ca2babcdb622" />

## ❓ Problem Statement

Given customer data including demographics, usage patterns, and service history, predict whether a customer is likely to churn (leave the service) in the near future.

## 📂 Dataset

- **Source**: [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features**:
  - Customer demographics
  - Account information
  - Service usage
  - Churn label (Yes/No)

## 🏗️ Project Architecture

```text
├── data/
│   └── raw/cleaned datasets
├── notebooks/
│   └── EDA and model development
├── src/
│   └── preprocessing.py
│   └── train_model.py
│   └── predict.py
├── models/
│   └── saved models
├── outputs/
│   └── results and visualizations
├── requirements.txt
└── README.md
```

## 🛠️ Technologies Used

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / LightGBM
- Streamlit (for optional dashboard)

## 🚀 Installation

```bash
git clone https://github.com/itshivam96/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
pip install -r requirements.txt
```

## 🧪 Usage

1. Place your dataset in the `data/` folder.
2. Run preprocessing:
   ```bash
   python src/preprocessing.py
   ```
3. Train the model:
   ```bash
   python src/train_model.py
   ```
4. Make predictions:
   ```bash
   python src/predict.py
   ```

## 📊 Results

- Achieved **accuracy of 85%** and **ROC-AUC of 0.89** using XGBoost.
- Feature importance analysis revealed that contract type and tenure are key indicators of churn.

## 🔮 Future Work

- Integrate real-time prediction API
- Deploy model using Flask or FastAPI
- Add explainability with SHAP values
- Build interactive dashboard with Streamlit

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.
