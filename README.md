# Predict Podcast Listening Time

## Overview
This project focuses on predicting podcast listening time using machine learning techniques. The goal is to analyze various podcast features (like episode length, host popularity, genre, etc.) to estimate how long listeners will engage with an episode. The project explores both Bayesian Neural Networks (BNN) and XGBoost models for this regression task.

## Features
- **Data Preprocessing**: Handles missing values, categorical encoding, and feature scaling.
- **Model Training**: Implements Bayesian Neural Networks (BNN) using Pyro and XGBoost.
- **Evaluation**: Measures performance using Mean Squared Error (MSE) and R-squared (R²).
- **Uncertainty Estimation**: BNN provides prediction intervals to quantify uncertainty.

## Results
- **Bayesian Neural Network (BNN)**:
  - Test MSE: **178.1412**
  - Test R²: **0.7579**
  - Provides uncertainty estimates with 95% confidence intervals.

- **XGBoost Model**:
  - Mean Squared Error: **168.72895445029815**
  - R-squared: **0.7706949086718065**
  - Achieved a Kaggle leaderboard score of **2875**.

## Performance Notes
- The current results are decent but not optimal. There is room for improvement through:
  - Hyperparameter tuning.
  - Feature engineering.
  - Model architecture enhancements.
  - Ensemble methods.

## Kaggle Competition
- **Competition Link**: [Playground Series S5E4](https://www.kaggle.com/competitions/playground-series-s5e4)
- **My Submission**: [GitHub Repository](https://github.com/mohamed682004/Predict-Podcast-Listening-Time)

## Future Work
- Experiment with deeper neural networks or transformer-based models.
- Incorporate additional features like podcast descriptions (NLP).
- Optimize training pipelines for better convergence.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/mohamed682004/Predict-Podcast-Listening-Time.git
   ```
2. Install dependencies:
   ```bash
   pip install tensorflow torch pyro-ppl scikit-learn xgboost pandas numpy
   ```
3. Run the Jupyter notebook or Python script to train and evaluate models.

## Contributions
Contributions and suggestions for improving the model are welcome! Feel free to fork the repository and submit pull requests.
