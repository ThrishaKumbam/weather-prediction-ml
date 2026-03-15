# Weather Prediction Using Machine Learning

This repository contains a machine learning project that predicts weather conditions using historical weather data. The project was completed as part of the **Applied Machine Learning** course in the **Master’s in Computer Science program at SUNY Polytechnic Institute**, under the guidance of **Prof. Amir Manzourolajdad**.

## Project Overview

Weather forecasting is an important application of machine learning. This project analyzes historical weather data and applies machine learning classification models to predict weather conditions.

The project includes data preprocessing, exploratory analysis, model training, and performance evaluation using multiple machine learning algorithms.

## Dataset

The project uses the **Seattle Weather Dataset**, which includes features such as:

- precipitation
- maximum temperature
- minimum temperature
- wind speed
- weather condition

The dataset is stored in:
seattle-weather.csv

## Machine Learning Models Used

The following machine learning models were used in this project:

- Gaussian Naive Bayes
- Random Forest Classifier
- Support Vector Classifier (SVC)
- Multi-Layer Perceptron (MLP)

## Methodology

The workflow of the project includes:

1. Loading and inspecting the dataset  
2. Data cleaning and preprocessing  
3. Feature transformation and encoding  
4. Exploratory data analysis and visualization  
5. Splitting the dataset into training and testing sets  
6. Training machine learning models  
7. Evaluating model performance and comparing results  

## Project Files

The repository currently contains the following files:
```
WEATHER-PREDICTION-ML
│
├── Weather_Prediction.ipynb
│ Jupyter notebook containing the machine learning workflow
│
├── seattle-weather.csv
│ Dataset used for training and testing
│
├── climate-and-weather-project-report.docx
│ Final project report
│
├── requirements.txt
│ Python dependencies required to run the project
│
└── .gitignore
  Git ignored files configuration
```

## How to Run the Project

### 1. Clone the repository
git clone <repo-url>
cd weather-prediction-ml

### 2. Install dependencies
pip install -r requirements.txt

### 3. Launch Jupyter Notebook
jupyter notebook

Then open:
Weather_Prediction.ipynb

## Results

Different machine learning models were evaluated and compared. The analysis shows that **Random Forest provided the best performance for predicting weather conditions** on this dataset.

## Learning Outcomes

This project helped develop practical understanding of:

- machine learning pipelines
- data preprocessing
- feature engineering
- classification algorithms
- model evaluation
- data visualization

## Academic Context

This project was completed for the course:

**Applied Machine Learning**  
Master’s in Computer Science  
**SUNY Polytechnic Institute**

Instructor: **Prof. Amir Manzour**

## Author

**Thrisha Reddy Kumbam**  
Master’s Student – Computer Science  
SUNY Polytechnic Institute  

GitHub: https://github.com/ThrishaKumbam
