# PDS-08-07
Here is the project about project
# Loan Default Prediction Using Logistic Regression

This repository contains a Python project that predicts whether a loan applicant will default using a logistic regression model. The project covers data preprocessing, visualization, model training, and evaluation.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The main objective of this project is to predict loan default by performing the following steps:

- **Preprocessing:**  
  - Fill missing values in numerical features with the column mean.
  - Fill missing values in categorical features with the mode.
  - Convert categorical features to numerical values using label encoding.

- **Visualization:**  
  - Plot loan approval rates based on income levels using bar charts.

- **Modeling:**  
  - Train a logistic regression model.
  - Evaluate model performance using precision–recall curves.

## Dataset

The project uses the [Loan Prediction Dataset from Kaggle](https://www.kaggle.com/datasets). Please download the dataset (for example, `loan_data.csv`) and place it in the `data/` directory.

## Installation

Clone the repository and install the required packages. It is recommended to use a virtual environment.

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# (Optional) Create and activate a virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

