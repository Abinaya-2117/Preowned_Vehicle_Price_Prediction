# Pre-Owned Vehicle Price Prediction Web Application

A machine learning–powered web application that predicts the selling price of pre-owned vehicles based on key car attributes. This project includes complete data preprocessing, model training, evaluation, and a Flask-based web interface for real-time predictions.

## Project Overview
This project uses regression-based machine learning models to estimate the selling price of used cars. A user-friendly web form collects vehicle features and returns the predicted value instantly.

## Model File (Download)
Since GitHub enforces a file size limit, the trained model (`best_model.pkl`) is hosted externally.

👉 **Model Download Link:** https://drive.google.com/file/d/1qIs0cZSpVHoi5IXf60WFD9GkhKz-WvJy/view?usp=sharing

## Features
- Predicts car selling price based on:
  - Age
  - Kilometers driven
  - Mileage
  - Engine capacity
  - Max power
  - Seats
  - Fuel type
  - Seller type
  - Transmission type
- Clean and simple web interface
- Fully implemented backend with Flask
- Machine learning workflow included end-to-end

## Machine Learning Models
Trained and evaluated multiple regression models:
- Decision Tree Regressor
- Random Forest Regressor (Selected as best performing)

The final exported model is saved as `best_model.pkl`.

## Tech Stack
- Python
- Flask
- HTML / CSS
- Scikit-learn
- NumPy & Pandas

## Project Structure
Own_Car_Pred_App/
│── app.py
│── /templates
│     └── index.html
│── /static
      └── style.css

Note: `best_model.pkl` should be downloaded from the link above and placed in the project directory.

## How to Run the Project
### 1. Install required libraries
pip install flask numpy pandas scikit-learn

### 2. Download `best_model.pkl` from the link above and place it into the project directory

### 3. Run Flask server
python app.py

### 4. Open in browser
http://localhost:8001

## Notes
- GitHub cannot store files above 100 MB (or large binary files), so the model file is hosted externally.
- Using external storage like Google Drive ensures the repo remains lightweight and easy to clone.

## Summary
This project demonstrates a complete ML pipeline — from data cleaning and model selection to deploying a functional prediction system using Flask. It is ideal for academic submissions, portfolio projects, and real-world ML deployment practice.
