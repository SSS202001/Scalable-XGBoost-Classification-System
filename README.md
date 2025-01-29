
# High-Performance XGBoost Models for Scalable Classification Systems

The project focuses on building a high-performance classification model using XGBoost, from data exploration and preprocessing to model training and deployment. The pipeline is designed for scalability and efficiency, suitable for integration into real-world applications.




## Dataset

The dataset used in this project was artificially generated and provided by the professor in my college. It consists of 1.2 million rows and 16 columns, including the target variable, Class, which is the primary focus of the classification task. This large dataset was specifically designed to simulate real-world scenarios, enabling the development and evaluation of predictive models in a controlled environment. The dataset offers diverse features that allow for in-depth analysis and model training, making it an ideal resource for this machine learning project.

I have included only a small portion of the dataset here due to the large size of the full file. If you require access to the entire dataset, please feel free to reach out to me at siddhantsarnobat20@gmail.com, or you can access the full dataset via this Google Drive link: https://drive.google.com/drive/folders/1WwZpfLCrK5S4GK3bl3MGyo2BGKqu9gN4?usp=sharing

## Project Structure

#### 1. Data Exploration and Preprocessing
Reading the Data: Load the dataset into a Pandas DataFrame.

Cleaning: Drop irrelevant columns, handle missing values, and encode categorical variables.
#### 2. Feature Engineering
Correlation & Multicollinearity: Analyze feature relationships and check for multicollinearity using VIF.

Balancing & Outlier Removal: Balance the data using SMOTE and remove outliers with Isolation Forest.
#### 3. Model Building and Evaluation
Model Selection & Training: Train an XGBoost model on the preprocessed data.

Evaluation: Assess performance using metrics like accuracy, precision, recall, and F1-score.
#### 4. Hyperparameter Tuning
Optimization: Tune hyperparameters with grid or random search, using ROC AUC for evaluation.
#### 5. Model Validation
Test Set Evaluation: Evaluate model performance on a holdout test set.

Model Comparison: Compare XGBoost with a baseline model.
## Appendix

The following appendices describe the purpose and actions taken in each notebook throughout the project:

#### 1. Exploratory Data Analysis (EDA)
This notebook cleans and prepares the data by handling missing values, identifying inconsistencies, and visualizing data distributions.

#### 2. Data Processing
Preprocessing steps are applied, including outlier removal, VIF analysis to address multicollinearity, and feature normalization.

#### 3. Data Analysis
Statistical summaries, visualizations, and correlation analysis are performed to identify trends and relationships in the data.

#### 4. Hyperparameter Tuning
The XGBoost model's hyperparameters are optimized using GridSearchCV or RandomizedSearchCV for improved performance.

#### 5. Model Training and Validation
The XGBoost model is trained, evaluated, and compared to a Naive Bayes model. The best model is saved as an ONNX file.

#### 6. Model Run Script
This notebook automates the prediction process by loading the trained model, preprocessing new data, and generating predictions.


## Authors

This project was developed by Siddhant Sarnobat for educational purpose.


## Contributing

Contributions are always welcome!

I welcome contributions from the community to enhance and expand this project. Please feel free to submit pull requests or raise issues if you have any suggestions or improvements.

## Deployment

The model is designed to be deployed in production. You can integrate the trained XGBoost model saved as an ONNX file into a production pipeline that processes new data and makes predictions.


## Documentation

Project documentation is included within the project report and this README.


## Environment Variables

This project relies on several environment variables for configuration. The .env file, which is included in the repository, contains all the necessary variables for running the project. Make sure to create a .env file in your local environment or production server and populate it with the following variables.


## Features

- Data Preprocessing Pipeline
- XGBoost Model Training and Evaluation
- Hyperparameter Tuning with Cross-Validation
- Model Export to ONNX Format for Deployment
- Automated Prediction for New Data
- Scalable Data Processing and Model Training
- Easy Integration for Production Use


## Feedback

I value your feedback! If you have any comments, suggestions, or questions regarding this project, please feel free to reach out to us at siddhantsarnobat20@gmail.com

## 🚀 About Me

Passionate data science student interested in data analysis and machine learning.


## Github Profile - Introduction

Welcome to my GitHub profile! Here you'll find various data science projects showcasing my skills and interests.

## 🔗 Links

LinkedIn - www.linkedin.com/in/siddhant-sarnobat

## Other Common Github Profile Sections

Feel free to check out my other projects on GitHub

## 🛠 Skills

- Python
- Machine Learning
- Big Data
- Data Cleaning and Transformation
- Data Preprocessing and Feature Engineering
- Model Training and Evaluation
- Hyperparameter Tuning
- Model Deployment


## Installation

To set up the environment for this project, clone this repository and install the required dependencies.

## Tech Stack

This project uses the following technologies and libraries:

- XGBoost: For building the classification model.
- ONNX: To save and load the trained model for inference.
- ONNX Runtime: For running the ONNX model.
- Pandas: Data manipulation and cleaning.
- NumPy: Numerical operations.
- Scikit-learn: For model evaluation and hyperparameter tuning.
- Matplotlib: Data visualization.

## Conclusion

This project successfully built a predictive model using an artificially generated dataset. Through data preprocessing, model training, and hyperparameter tuning, the XGBoost model achieved strong performance in classifying the target variable. 