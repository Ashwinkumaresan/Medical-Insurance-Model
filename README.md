# 📊 Medical Insurance Charges Prediction

This project predicts medical insurance charges based on demographic and health-related attributes using a **Linear Regression** model. It involves data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Project Workflow](#project-workflow)
- [Model Evaluation](#model-evaluation)
- [Setup & Installation](#setup--installation)
- [How to Run](#how-to-run)
- [Files Included](#files-included)
- [Technologies Used](#technologies-used)
- [Contact](#contact)
- [License](#license)

---

## 📑 Project Overview

The goal of this project is to estimate the **medical insurance charges** for individuals based on attributes like:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

By training a regression model on historical data, we aim to predict medical expenses for new entries.

---

## 📦 Dataset Description

The dataset contains the following columns:

- `age`: Age of the person
- `sex`: Gender of the person (`male`, `female`)
- `bmi`: Body Mass Index
- `children`: Number of children the person has
- `smoker`: Smoking status (`yes`, `no`)
- `region`: Residential region (`southwest`, `southeast`, `northwest`, `northeast`)
- `charges`: Insurance charges (target variable)

---

## 📊 Project Workflow

1. **Import Libraries**
2. **Load Dataset**
3. **Perform Data Preprocessing**
   - Handling categorical data
   - Encoding string labels into numerical values
4. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Correlation heatmaps
   - Histograms
5. **Train-Test Split**
6. **Model Building**
   - Linear Regression
7. **Model Evaluation**
   - Calculate **RMSE (Root Mean Squared Error)**

---

## 📈 Model Evaluation

The model’s performance was evaluated using **Root Mean Squared Error (RMSE)**, a standard regression metric for assessing prediction accuracy.

Example result:
- **RMSE**: `2.0` (lower is better)

---

## 🛠️ Setup & Installation

### 📌 Prerequisites

- Python 3.x
- Jupyter Notebook

---

### 📦 Install Dependencies

Clone this repository and install the required dependencies using:

```bash
pip install -r requirements.txt
