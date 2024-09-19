# MediSense AI

**MediSense AI** is an all-in-one disease detection app built using Streamlit and machine learning algorithms. The app can predict diseases such as heart disease, diabetes, and more based on user input data. It utilizes several machine learning models to provide accurate and efficient predictions, empowering users to assess their health risks easily.

## Features

- **Disease Prediction**: Predicts various diseases, including heart disease and diabetes, using machine learning models.
- **Streamlit Interface**: A user-friendly, interactive interface for inputting health data and receiving predictions.
- **Multiple Algorithms**: Supports different machine learning algorithms for accurate disease detection.
- **Real-time Results**: Displays real-time predictions after the user submits their health data.

## Tech Stack

- **Backend**: Python, Scikit-learn, NumPy, Pandas
- **Frontend**: Streamlit
- **Machine Learning Models**: Logistic Regression, Decision Trees, Random Forest, etc.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- pip (Python package installer)

## Setup and Installation

Follow these steps to set up and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Kulashekar01/MediSense-AI.git
cd MediSense-AI
```

### 2. Create and Activate Virtual Environment (Optional but recommended)

```bash
# Create virtual environment
python -m venv env

# Activate virtual environment
# For Windows:
env\Scripts\activate
# For macOS/Linux:
source env/bin/activate
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Your Dataset (If Required)

Ensure the dataset required for training or predictions is in the appropriate directory. You can modify the dataset paths in the script if needed.

### 5. Run the Application

To run the app locally, use the following command:

```bash
streamlit run app.py
```

This will start the Streamlit server, and you can access the app in your browser at:

```
http://localhost:8501
```

### 6. Using the App

- Open your browser and navigate to `http://localhost:8501`.
- Enter the required health data (like age, blood pressure, cholesterol levels, etc.).
- Submit the data to get predictions for various diseases.

## Project Structure

```
├── app.py                   # Main Streamlit app
├── models/                  # Trained ML models
├── data/                    # Datasets used for training/prediction
├── requirements.txt         # List of required Python packages
└── README.md                # Project documentation
```

## Dependencies

Ensure the following packages are installed (included in `requirements.txt`):

- streamlit
- scikit-learn
- numpy
- pandas

To install all dependencies, run:

```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your fork.
4. Open a pull request with a description of your changes.
