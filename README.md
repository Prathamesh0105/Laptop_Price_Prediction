# LaptopPricing MachineLearning Analysis

## Introduction
This repository contains the analysis and machine learning model implementation for the laptop-pricing dataset. The goal is to predict various price of laptops having various attributes using different machine learning techniques.

## Table of Contents
1. Data Import and Cleaning
2. Exploratory Data Analysis (EDA)
3. Model Evaluation
4. Over-fitting, Under-fitting, and Model Selection
5. Ridge Regression
6. Grid Search

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Tools**: Jupyter Notebook

## Getting Started
To get started with this project, clone the repository and install the necessary dependencies:
```bash
git clone https://github.com/Prathamesh0105/Laptop_Price_Prediction.git
cd Laptop_Price_Prediction
pip install -r requirements.txt
```

## Usage
Open the Jupyter notebook:
```bash
jupyter notebook LaptopPricing-ML.ipynb
```

## Dataset
The dataset used in this analysis is LaptopPricing.csv, which contains various features related to laptops such as CPU_frequency, RAM_GB, Storage_GB_SSD , CPU_core , OS , GPU, Category and price.

## R^2 scores
<div align="center">
  
  **R^2** scores of the **Linear Regression** model created using different degrees of polynomial features, ranging from 1 to 5.
  <img src="src/R2_1.png" alt="R2_polynomial-features" width="800"/>
  
  **R^2** values of **Ridge Regression** model for training and testing sets with respect to the values of alpha.
  <img src="src/R2_2.png" alt="R2_for-alphas" width="800"/>
</div>

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests.

## License
This project is licensed under the MIT License.
