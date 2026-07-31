# Data Center Water & Electricity Usage Prediction

## Project Overview

This project focuses on cleaning, analyzing, and modeling data related to global data centers. The objective is to understand the factors affecting water and electricity consumption and build machine learning models capable of predicting resource usage.

The project is divided into two stages:

1. Data Cleaning & Exploratory Data Analysis (EDA)
2. Machine Learning Modeling

---

## Project Structure

```
.
├── README.md
├── notebooks
│   ├── 01_data_cleaning_and_eda.ipynb
│   └── 02_machine_learning.ipynb
├── data
│   ├── raw
│   └── processed
├── images
└── requirements.txt
```

---

## Dataset

The dataset contains information about data centers worldwide, including:

* Facility information
* Country
* City
* Owner company
* Capacity (MW)
* Cooling system
* Water Usage Effectiveness (WUE)
* Power Usage Effectiveness (PUE)
* Daily water usage
* Daily electricity usage
* Water stress level

---

## Notebook 1 – Data Cleaning & EDA

This notebook performs:

* Importing the raw dataset
* Cleaning country names
* Removing invalid country records
* Normalizing company names
* Cleaning city information
* Removing duplicates
* Handling missing values
* Exploratory Data Analysis
* Preparing a clean dataset for modeling

---

## Notebook 2 – Machine Learning

This notebook performs:

### Feature Engineering

* Water per MW
* Electricity per MW
* High water stress indicator

### Data Preprocessing

* One-hot encoding of categorical features
* Numerical feature scaling (where required)

### Machine Learning Models

Several regression models are trained and compared for predicting:

* Daily Water Usage
* Daily Electricity Usage

The notebook also includes:

* Model evaluation
* Feature importance analysis
* Performance comparison

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## How to Run

1. Clone the repository.

```
git clone https://github.com/yourusername/data-center-water-electricity-prediction.git
```

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter Notebook or VS Code.

4. Run:

* `01_data_cleaning_and_eda.ipynb`
* `02_machine_learning.ipynb`

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost and LightGBM models
* Model deployment using Streamlit or Flask
* Interactive dashboard for resource prediction

---

## Author

Your Name
