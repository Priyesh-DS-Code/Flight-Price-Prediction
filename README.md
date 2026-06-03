# ✈️ Flight Price Prediction System

## Overview

Flight Price Prediction System is a Machine Learning project designed to estimate airline ticket prices based on various flight-related attributes such as airline, source city, destination city, journey date, duration, and number of stops.

The project demonstrates the complete machine learning lifecycle, including data collection, data cleaning, exploratory data analysis, feature engineering, model development, evaluation, and prediction. The objective is to build a reliable predictive model that can assist travelers and businesses in estimating airfare costs.

---

## Business Problem

Airline ticket prices are highly dynamic and influenced by multiple factors, including travel season, airline selection, route popularity, flight duration, and stopovers.

Accurately predicting airfare can help:

* Travelers make informed booking decisions
* Businesses analyze airline pricing strategies
* Travel platforms improve price forecasting
* Data analysts identify key pricing drivers

This project aims to develop a data-driven solution capable of estimating flight ticket prices using historical flight booking data.

---

## Dataset Information

The dataset contains flight booking information collected from various airlines and routes.

### Features

| Feature                | Description                   |
| ---------------------- | ----------------------------- |
| Airline                | Airline operating the flight  |
| Date of Journey        | Travel date                   |
| Source                 | Departure city                |
| Destination            | Arrival city                  |
| Route                  | Flight route                  |
| Departure Time         | Flight departure time         |
| Arrival Time           | Flight arrival time           |
| Duration               | Total flight duration         |
| Total Stops            | Number of intermediate stops  |
| Additional Information | Additional flight information |

### Target Variable

| Variable | Description         |
| -------- | ------------------- |
| Price    | Airline ticket fare |

---

## Key Highlights

* End-to-End Machine Learning Workflow
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Business-Oriented Insights
* Production-Ready Repository Structure

---

## Tech Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

### Development Environment

* Jupyter Notebook

### Version Control

* Git
* GitHub

### Future Deployment Stack

* Streamlit
* Docker
* AWS

---

## Project Structure

```text
Flight-Price-Prediction/
│
├── data/
│   └── dataset.xlsx
│
├── notebooks/
│   └── Flight-Price-Prediction.ipynb
│
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Machine Learning Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
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

## Exploratory Data Analysis

The dataset was analyzed to understand pricing trends and identify important factors affecting airline fares.

Key analyses performed:

* Airline-wise price distribution
* Source and destination analysis
* Route popularity analysis
* Flight duration analysis
* Stop-wise fare comparison
* Journey date trends
* Correlation analysis

---

## Feature Engineering

The following feature engineering techniques were applied:

* Extracted journey day and month
* Extracted departure hour and minute
* Extracted arrival hour and minute
* Converted flight duration into numerical values
* Encoded categorical features
* Removed irrelevant columns

These transformations improved model performance and enabled machine learning algorithms to process the data effectively.

---

## Model Development

Multiple regression techniques can be evaluated to identify the best-performing model for airfare prediction.

The workflow includes:

* Data Splitting
* Feature Scaling (if required)
* Model Training
* Hyperparameter Optimization
* Model Selection

---

## Model Evaluation

The model was evaluated using standard regression metrics:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

These metrics help assess prediction accuracy and overall model performance.

---

## Key Insights

* Airline selection significantly impacts ticket prices.
* Flight duration strongly influences airfare.
* Journey dates affect seasonal pricing trends.
* Source and destination routes contribute heavily to fare variation.
* Number of stops impacts pricing patterns across airlines.

---

## Results

The machine learning model successfully learns relationships between flight characteristics and airfare pricing, enabling accurate ticket fare estimation based on user inputs.

The project demonstrates the practical application of machine learning techniques in solving real-world pricing and forecasting problems.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Priyesh-DS-Code/Flight-Price-Prediction.git
```

### Navigate to Project Directory

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

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Data Visualization
* Model Evaluation
* Business Analytics
* Machine Learning
* Python Programming

---

## Author

### Priyesh Kumar Kashyap

Machine Learning & Data Science Enthusiast focused on building end-to-end machine learning solutions and production-ready AI applications.

**Areas of Interest**

* Machine Learning
* Data Science
* MLOps

**Connect With Me**

GitHub: https://github.com/Priyesh-DS-Code

LinkedIn: https://www.linkedin.com/in/priyeshkumarkashyap

*"Transforming data into intelligent solutions through Machine Learning and Data Science."*
