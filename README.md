# 🏙️ Air Pollution Classification Based on Weather Conditions in Jakarta

This repository contains the code and datasets used for the research project **"Classification of Jakarta’s Air Pollution Index Based on Weather Conditions Using Machine Learning Algorithms"**.

## 📌 Project Overview

The goal of this project is to classify Jakarta's **Air Pollution Index (ISPU)** levels based on various weather conditions using machine learning techniques. This classification can help provide early warning systems and assist in environmental monitoring and policy-making.

## 📊 Dataset

The dataset used in this project is a combination of:
- **Air Quality Data:** Collected from [Satudata Jakarta](https://satudata.jakarta.go.id/) (2021–2024)
- **Weather Data:** Collected from [Visual Crossing](https://www.visualcrossing.com/) for Jakarta city

After integration, the dataset includes features such as:
- Temperature
- Humidity
- Wind Speed
- Precipitation
- Air Quality Parameters (e.g., PM2.5, PM10, CO, O3)

## ⚙️ Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Feature encoding and scaling
   - Dataset integration based on timestamps

2. **Feature Selection**
   - Pearson Correlation
   - Random Projection

3. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - K-Fold Cross Validation


## 📦 Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib / seaborn
