# 💎 Gemstone Price Prediction MLOps Project

<div align="center">

![Gemstone Price Prediction](https://img.shields.io/badge/Project-Gemstone%20Price%20Prediction-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8%2B-yellow?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-green?style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black?style=for-the-badge&logo=flask)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue?style=for-the-badge&logo=docker)
![MLOps](https://img.shields.io/badge/MLOps-End--to--End-purple?style=for-the-badge)

### End-to-End Machine Learning Project for Predicting Gemstone Prices

**Built by Hritik Patil**

</div>

---

## 📌 Project Overview

This project is an end-to-end **Gemstone Price Prediction** machine learning application.

The goal of this project is to predict the price of a gemstone/diamond based on important features such as carat, cut, color, clarity, depth, table, and physical dimensions.

This project is designed using a complete machine learning and MLOps workflow, including data ingestion, data transformation, model training, prediction pipeline, Flask web application, Docker support, and deployment-ready structure.

---

## 🎯 Problem Statement

Gemstone pricing depends on several physical and quality-based features. Manual price estimation can be inconsistent, time-consuming, and difficult for large datasets.

The objective of this project is to build a machine learning regression model that predicts the `price` of a gemstone using its given characteristics.

This is a **supervised regression problem**.

---

## 🧠 Key Highlights

- End-to-end machine learning pipeline
- Clean modular project structure
- Data ingestion and transformation pipeline
- Multiple regression model comparison
- Best model selection
- Flask-based web application
- Prediction pipeline for real-time input
- Docker support
- MLOps-ready architecture
- Notebook-based EDA and model experimentation

---

## 📊 Dataset Information

The dataset is taken from Kaggle Playground Series.

Dataset Source:  
[Gemstone Price Prediction Dataset](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)

The target variable is:

| Column | Description |
|---|---|
| `price` | Price of the gemstone/diamond |

The independent features are:

| Feature | Description |
|---|---|
| `id` | Unique identifier for each gemstone |
| `carat` | Weight of the gemstone |
| `cut` | Quality of the diamond cut |
| `color` | Color grade of the diamond |
| `clarity` | Clarity grade of the diamond |
| `depth` | Depth percentage of the diamond |
| `table` | Width of the top facet of the diamond |
| `x` | Length of the diamond |
| `y` | Width of the diamond |
| `z` | Depth/height of the diamond |

---

## 💡 Important Data Observation

The categorical columns below are ordinal in nature:

```text
cut
color
clarity
