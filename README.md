# hotel-booking-cancellation-prediction
Hotel booking cancellation prediction using Python and machine learning.
Project Overview

This project aims to predict whether a hotel booking will be canceled using historical reservation data and machine learning. The goal is to help hotels improve room planning and reduce potential revenue losses.

Dataset

Name: Hotel Booking Demand

Source: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

Licence: CC BY 4.0

Original dataset: 119,390 rows and 32 columns

Cleaned dataset: 119,209 rows and 33 columns

Target variable: is_canceled

Data Preparation

We used Python and Jupyter Notebook to:

Explore the dataset and identify data quality issues.

Handle missing values.

Investigate duplicate records.

Remove invalid bookings.

Check inconsistent categorical values and outliers.

Create a new arrival date column.

Save the cleaned dataset for further analysis.

Project Files

01_Hotel_Booking_Data_Preparation.ipynb — Data exploration and cleaning notebook.

hotel_bookings_cleaned.csv — Cleaned dataset.

Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

How to Run

Download the repository.

Install the required Python libraries.

Download the original hotel_bookings.csv from the Kaggle source above.

Place the original CSV in the same folder as the notebook.

Open the notebook in Jupyter and run all cells in order.

Project Status

Stages 1–3: Business problem formulation, dataset selection, and data preparation.

EDA, feature engineering, machine learning, model evaluation, and Streamlit deployment will be completed in later stages.
