# ✈️ Flight Price Prediction

An end-to-end Machine Learning project that predicts airline ticket prices based on flight details such as airline, source city, destination city, journey date, duration, and number of stops.

The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model training, and price prediction using machine learning techniques.

---

## Project Overview

Flight ticket prices fluctuate significantly depending on multiple factors including airline, route, travel date, duration, and stopovers.

The objective of this project is to analyze historical flight booking data and build a machine learning model capable of predicting flight fares accurately.

---

## Business Problem

Airfare pricing is dynamic and changes frequently due to demand, seasonality, route popularity, and airline policies.

This project aims to:

- Analyze factors affecting flight prices
- Understand airline pricing patterns
- Identify important features influencing ticket cost
- Build a predictive model for airfare estimation

---

## Dataset Information

The dataset contains flight booking information including:

### Features

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information

### Target Variable

- Price (Flight Fare)

---

## Technology Stack

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### Development Environment

- Jupyter Notebook

### Version Control

- Git
- GitHub

---

## Project Structure

```text
Flight-Price-Prediction/
│
├── Flight-prediction.ipynb
├── README.md
├── requirements.txt
└── dataset.xlsx
```

---

## Project Workflow

### 1. Data Collection

- Import flight booking dataset
- Understand feature distributions

### 2. Data Cleaning

- Handle missing values
- Remove duplicates
- Correct data inconsistencies

### 3. Exploratory Data Analysis

- Airline-wise price analysis
- Source and destination analysis
- Stop-wise fare analysis
- Duration vs Price relationship
- Journey date analysis

### 4. Feature Engineering

- Extract day and month from journey date
- Extract departure and arrival hours
- Convert duration into numerical format
- Encode categorical variables

### 5. Model Building

- Train machine learning models
- Compare model performance
- Select the best-performing model

### 6. Model Evaluation

Evaluation metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Key Insights

- Airline choice significantly impacts ticket prices.
- Flights with multiple stops generally have different pricing patterns compared to non-stop flights.
- Journey date and travel season strongly influence airfare.
- Flight duration is an important factor in fare prediction.
- Source and destination routes contribute significantly to ticket cost variation.

---

## Machine Learning Pipeline

```text
Data Collection
        ↓
Data Cleaning
        ↓
EDA
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Flight Price Prediction
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Priyesh-DS-Code/Flight-Price-Prediction.git
```

### Navigate to Project Folder

```bash
cd Flight-Price-Prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Results

The machine learning model successfully learns relationships between flight attributes and ticket prices, enabling accurate airfare predictions for future flight bookings.

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Cleaning
- Data Visualization
- Machine Learning
- Regression Modeling
- Model Evaluation
- Business Analytics
- Python Programming



---

## Author

**Priyesh Kumar Kashyap**

B.Tech Computer Science Engineering Student

Interested in:

- Machine Learning
- Data Science
- MLOps

GitHub: https://github.com/Priyesh-DS-Code

LinkedIn: https://www.linkedin.com/in/priyeshkumarkashyap

---
