# Dataset Information

## Pima Indians Diabetes Database

The dataset used in this project is the Pima Indians Diabetes Database, available on Kaggle.

**Dataset source:**  
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

## Dataset Characteristics

- Total records: 768
- Input features: 8
- Target variable: Outcome
- Non-diabetic records: 500
- Diabetic records: 268
- Training records: 614
- Testing records: 154

## Input Features

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skinfold thickness |
| Insulin | Serum insulin |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |

## Target Variable

- 0: Non-Diabetic
- 1: Diabetic

## Dataset Preprocessing

Invalid zero values in Glucose, BloodPressure, SkinThickness, Insulin and BMI are treated as missing values.

The dataset is divided into training and testing subsets using an 80:20 stratified split with random_state=42.

## Download Instructions

Download the dataset from the original source and prepare the headerless CSV file named `pima-indians-diabetes.csv`, with the eight features in the order listed above followed by Outcome.

Upload this file when prompted by the Google Colab notebook.

The original dataset is not redistributed in this repository pending confirmation of its redistribution permissions.

## Disclaimer

The dataset represents a specific study population. Models developed using this dataset are intended for educational machine learning experimentation and are not clinically validated diagnostic systems.
