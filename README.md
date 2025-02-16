# Recommendation Service using CatBoost

## 📌 Overview
This project is a **machine learning-based recommendation service** that processes post text, extracts features, and uses **CatBoost** for generating recommendations. The service is built for efficiency, integrating a database for fast retrieval and exposing an API via **FastAPI**.

✅ **Feature Engineering** – Extracted key text-based features  
✅ **Exploratory Data Analysis (EDA)** – Analyzed patterns in data  
✅ **Efficient Storage** – Features stored in a database for optimized speed  
✅ **Machine Learning Model** – CatBoost for accurate recommendations  
✅ **API Service** – Built with **FastAPI** for seamless integration  
✅ **Postman Integration**


## 📂 Project Structure
```bash
recommendation-service_ver1/      # Root directory of the project
│── README.md                # Project documentation
│── requirements.txt         # Dependencies list
│── .gitignore/               # Git ignore file
│── notebooks/               # Jupyter Notebooks for model training & feature engineering
│   ├── Feature_databases.ipynb # Feature extraction & database storage
│   ├── Model.ipynb             # Model training & evaluation
│── models/                  # Pre-trained models
│   ├── catboost_model_3.cbm      # Saved CatBoost model
│── service/                 # API implementation using FastAPI
│   ├── service.py              # API endpoints and service logic
│   ├── schema.py               # API schema definitions


