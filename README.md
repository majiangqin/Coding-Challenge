# Coding Challenge

This repository contains the code, data, and visualizations for a coding challenge project. The project focuses on exploratory data analysis (EDA), predictive modeling, and ensemble techniques to analyze and predict outcomes based on the provided datasets.

---

## Project Structure

The project is organized into the following folders and files:

### **Code/**
Contains Jupyter Notebooks with Python code for data analysis and modeling:
- `EDA.ipynb`: Exploratory Data Analysis (EDA) notebook for understanding the dataset and identifying key patterns.
- `SARIMAX.ipynb`: Implementation of the SARIMAX model for time series forecasting.
- `SARIMAX-XGBoost-Hybrid.ipynb`: A hybrid model combining SARIMAX and XGBoost for improved accuracy.
- `SARIMAX-XGBoost-fine-tuning.ipynb`: Fine-tuning of the hybrid model to optimize performance.
- `Spark-Triple-Ensemble-Model.ipynb`: Spark-based ensemble model for advanced performance.

### **Data/**
Contains datasets used for training and testing models:
- `sample_submission.csv`: Example of the submission format.
- `submission.csv`: The best model's submission file.

### **Plots/**
Contains visualizations and graphs generated during the EDA:
- Includes key charts such as correlation matrices, time series trends, and target distributions.

### **Project_Overview_Report.pdf**
A detailed report summarizing the objectives, methods, results, and conclusions of the project.

---

## Getting Started

### Prerequisites
To run this project, you need the following:
- Python 3.8 or higher
- Jupyter Notebook
- GPU (recommended for faster model training)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/majiangqin/Coding-Challenge.git
   ```
2. Navigate to the project directory:
    ```
    cd Coding-Challenge
    ```
3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
