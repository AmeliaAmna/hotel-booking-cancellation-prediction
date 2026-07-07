# Hotel Booking Cancellation Prediction

Machine learning case study predicting hotel booking cancellations to support
hotel management decisions, using the Kaggle Hotel Booking Demand dataset.

## Approach

- Exploratory data analysis on cancellation patterns by hotel type, lead time,
  deposit type, and market segment
- Data cleaning: removed leakage-prone columns (`reservation_status`,
  `reservation_status_date`), handled missing values, removed duplicates,
  encoded categorical features
- Trained and compared three classification models:
  - Logistic Regression (baseline)
  - Decision Tree
  - Random Forest
- Evaluated using accuracy, AUC, and ROC curves
- Analyzed feature importance to identify the strongest predictors of cancellation

## Key Finding

Random Forest outperformed the other two models on the evaluation metrics used.

## Tech Stack

Python · pandas · scikit-learn · matplotlib · seaborn

## Dataset

[Kaggle Hotel Booking Demand dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) —
not included in this repo; download `hotel_bookings.csv` separately and place
it in the same directory before running the notebook.

## Status

Completed as part of the Decision Analytics module — full report and viva
defense completed.
