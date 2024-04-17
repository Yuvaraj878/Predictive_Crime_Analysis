# Predictive_Crime_Analysis 🔍
🔍 Analyzing Complainant and Arrest Details Datasets
## Overview 📊

This project aims to analyze complainant and arrest details datasets to understand patterns and relationships within the data. The analysis includes exploratory data analysis (EDA), data preprocessing, and building a machine learning model to predict the sex of the individuals based on various features.

## Table of Contents 📑

- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Results and Evaluation](#results-and-evaluation)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset Overview 📋

The dataset consists of three main files:

- `ComplainantDetailsData.csv`: Contains details about complainants.
- `FIR_Details_Data.csv`: Contains details about First Information Reports (FIRs).
- `ArrestPersonDetails.csv`: Contains details about arrested persons.

## Exploratory Data Analysis 🔍

- Explored various features such as district name, age, nationality, occupation, etc.
- Checked for missing values and handled them appropriately.
- Visualized the count of arrest person details records by district using matplotlib.

## Data Preprocessing 🛠️

- Handled missing values by filling them with appropriate values.
- Encoded categorical variables using LabelEncoder from scikit-learn.
- Selected relevant features for building the machine learning model.

## Machine Learning Model 🤖

- Used RandomForestClassifier to predict the sex of individuals based on selected features.
- Split the data into train and test sets.
- Trained the model on the training set and evaluated its performance on the test set.

## Results and Evaluation 📈

- Achieved an accuracy of [insert accuracy score] on the test set.
- Generated a classification report and confusion matrix to further evaluate the model's performance.

## Conclusion 🎉

- The analysis provided insights into the dataset and helped in building a predictive model for identifying the sex of individuals.
- Further improvements could be made by exploring additional features or using more advanced machine learning techniques.

## Dependencies 📦

- pandas
- matplotlib
- scikit-learn

## Contributing 🤝
- YUVARAJ S
- SANDHYA BN
- NIURANJANA GAYATHRI GR
- SHALINI K

## License 📄

- This project is licensed under the MIT License.
