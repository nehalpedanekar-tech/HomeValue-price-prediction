# HomeValue 🏠

HomeValue is a house price prediction project with a complete machine learning backend. It trains a Random Forest Regressor on housing data and serves predictions through a FastAPI REST API, with PostgreSQL used to store data.

## Features
- Predicts house prices from input features through an API endpoint
- Random Forest Regressor model with an R² score of about 0.80
- Trained model saved and loaded with joblib
- PostgreSQL integration using SQLAlchemy

## Tech stack
Python, pandas, scikit-learn, FastAPI, PostgreSQL, SQLAlchemy, joblib

## How to run
1. Clone the repo and create a virtual environment
2. `pip install -r requirements.txt`
3. Set your database details in a `.env` file
4. Run the server: `uvicorn main:app --reload`
5. Open `http://127.0.0.1:8000/docs` to try the API
