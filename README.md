# Boston Housing Price Prediction

This project builds a linear regression model to predict housing prices in Boston using the Boston Housing dataset. The goal is to analyze various housing features and estimate property prices.

## Project Overview

- Dataset: Boston Housing dataset
- Model: Linear Regression
- Evaluation Metric: R² Score (~0.67)
- Key Features: Crime rate, average rooms, property tax, distance to employment centers, and more
- Model saving: The trained model is saved using `pickle` for later use or deployment

## How to Use

1. Clone the repository.
2. Train the model by running the notebook or Python script (`train_model.ipynb` or `train_model.py`).
3. Save the trained model using pickle.
4. Load the saved model to make predictions on new data.
5. (Optional) Use the provided Streamlit/Gradio app for interactive predictions.

## Results

- The model achieves an R² score of approximately 0.67, indicating it explains about 67% of the variance in housing prices.
- Some limitations include occasional negative predictions, which can be clipped or addressed through model improvements.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy
- pickle
- (Optional: Streamlit or Gradio for frontend)

## Next Steps

- Improve model accuracy with feature engineering or advanced models (Ridge, Lasso, Random Forest)
- Build an interactive frontend for user inputs and predictions
- Deploy the model as a web app or API

---

Feel free to contribute or raise issues!

