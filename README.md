# CuraMetric 🏥

CuraMetric is a machine learning-powered health care premium prediction system. It leverages user demographic, lifestyle, and medical history data to accurately estimate health insurance costs.

## 🌟 Features

- **Personalized Predictions**: Predicts insurance costs based on comprehensive individual user profiles.
- **Risk Analysis**: Considers a wide array of factors including genetic risk, medical history (e.g., diabetes, high blood pressure, thyroid, heart disease), and lifestyle choices (e.g., smoking status, BMI category).
- **Segmented ML Models**: Utilizes specialized machine learning models segmented by age (e.g., young adults vs. rest of the population) to ensure higher prediction accuracy.
- **Interactive UI**: Built with Streamlit, providing a clean, intuitive, and real-time web interface for users to input their data and receive instant estimates.

## 🛠️ Tech Stack

- **Frontend/UI**: Streamlit
- **Machine Learning**: Scikit-Learn, Pandas, Joblib
- **Language**: Python

## 📁 Project Structure

- `app/`: Contains the Streamlit web application.
  - `main.py`: The main entry point for the Streamlit application interface.
  - `prediction_helper.py`: Helper functions for data preprocessing, scaling, and model inference.
  - `artifacts/`: Serialized pre-trained machine learning models (`.joblib` files) and scalers.
- `*.ipynb`: Jupyter Notebooks used for exploratory data analysis (EDA), data segmentation, and training the predictive models.
- `*.xlsx`: Datasets used for training and evaluating the models.

## 🚀 Getting Started Locally

### Prerequisites

Ensure you have Python installed. You can install the required dependencies using `pip`.

```bash
pip install -r requirements.txt
```

*(If you don't have a `requirements.txt` yet, you can install the dependencies manually: `pip install streamlit pandas scikit-learn joblib`)*

### Running the Application

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AbhiramRaja/CuraMetric.git
   cd CuraMetric
   ```

2. **Navigate to the application directory**:
   ```bash
   cd app
   ```

3. **Run the Streamlit application**:
   ```bash
   streamlit run main.py
   ```

The application should now be running on `http://localhost:8501`.
