
# Heart Disease Prediction Using Machine Learning

## Project Overview
This project aims to predict the presence of heart disease in patients based on various health-related parameters using **Machine Learning** techniques. The dataset contains multiple attributes such as age, cholesterol, blood pressure, chest pain type, and other diagnostic measures to predict whether a patient has heart disease or not.

## Table of Contents
1. [Project Description](#project-description)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model](#model)
6. [Tools & Technologies](#tools--technologies)
7. [License](#license)

## Project Description
The project involves analyzing patient health data and using **Logistic Regression** for predicting the presence of heart disease. The goal is to provide an accurate model that can assist healthcare professionals in early diagnosis. 

Key steps in the project:
- Data analysis and exploration
- Data preprocessing and feature engineering
- Model training using **Logistic Regression**
- Model evaluation and optimization

## Dataset
The dataset used in this project is the **Heart Disease UCI dataset** available on the UCI Machine Learning Repository. The dataset includes various medical features like:
- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thallium Heart Scan
- Target (Presence of Heart Disease)

For more details, check the dataset description [here](https://archive.ics.uci.edu/ml/datasets/heart+disease).

## Installation

### Prerequisites
Make sure you have Python installed (version 3.6+). You will also need to install the required Python libraries.

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script to start the data analysis and model training:
   ```bash
   python heart_disease_prediction.py
   ```
2. The script will:
   - Load and preprocess the dataset
   - Train a **Logistic Regression** model
   - Evaluate the model’s accuracy and performance

## Model
The model used for classification is **Logistic Regression**, which was selected after performing an extensive analysis of the data. Key evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-Score

## Tools & Technologies
- **Python**
- **Pandas**: Data manipulation and analysis
- **Numpy**: Numerical computing
- **Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning algorithms and tools
- **Logistic Regression**: Model used for classification
- **Machine Learning**: General techniques applied

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
