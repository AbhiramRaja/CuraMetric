# CuraMetric - Health Care Premium Prediction

This project contains machine learning models and a Streamlit web application to predict health care premiums based on user metrics.

## Project Structure
- Various Jupyter Notebooks for data preprocessing, segmentation, and machine learning model training (`ml_premium_prediction_*.ipynb`).
- Datasets containing the required information.
- An `app/` folder containing the Streamlit web application (`main.py`) which utilizes the trained models to provide realtime predictions.

## Running the Streamlit App Locally

Ensure you have the necessary dependencies installed (e.g., `streamlit`, `pandas`, `scikit-learn`, etc).

Navigate to the `app` directory and start the Streamlit server:
```bash
cd app
streamlit run main.py
```
