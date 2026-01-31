# Room Reservation Cancellation Prediction

**Author:** Sophia Amsden  
**Course:** BUS 458 (001)  
**Date:** November 13, 2025

## Project Overview
This project predicts whether a hotel booking will be canceled using machine learning. Models used include Logistic Regression, Random Forest, and XGBoost. SHAP is used to explain feature importance.

## Data
The dataset contains hotel reservation details (number of guests, room type, lead time, previous cancellations, etc.) and the booking status (`Canceled` or `Not_Canceled`). You will need to provide the CSV file `Hotel Reservations.csv` in the `data/` folder.

## Features
Key features include:
- Number of adults and children
- Room type and meal plan
- Lead time and arrival date
- Previous cancellations and special requests

## Models
- **Logistic Regression**
- **Random Forest** (best performing)
- **XGBoost**

## How to Use
1. Clone this repository.
2. Place the dataset in the `data/` folder.
3. Run the Jupyter notebook `BUS458_HW3_RoomReservations.ipynb` to reproduce results and visualizations.

## Results
- Model evaluation includes accuracy, precision, recall, F1, and ROC AUC.
- Random Forest was the best-performing model on the test set.
- SHAP plots highlight the most important features influencing cancellations.
