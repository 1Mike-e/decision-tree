# Decision Tree Classifier on Social Network Ads

This project implements a Decision Tree classifier to predict whether a user purchases a product based on their age and estimated salary using the `Social_Network_Ads.csv` dataset.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [License](#license)

## Overview

The objective is to classify users into:
- **Purchased (1)**
- **Not Purchased (0)**

This classification is performed using a **Decision Tree Classifier** from `scikit-learn` with the **entropy** criterion. The pipeline includes:
- Data preprocessing
- Train/test split
- Feature scaling
- Model training
- Prediction and evaluation
- Visualizations of decision boundaries

## Dataset

The dataset used is `Social_Network_Ads.csv`, which must include:
- `Age`
- `Estimated Salary`
- `Purchased` (target variable)

## Installation

1. Clone the repository or copy the script locally.
2. Install required Python packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
