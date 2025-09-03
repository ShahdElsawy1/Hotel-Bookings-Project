# Hotel-Bookings-Project
📌 Project Overview

This project analyzes the Hotel Bookings dataset and builds a machine learning pipeline to predict booking cancellations. The goal is to clean and prepare the data, engineer meaningful features, handle categorical variables, and create a dataset suitable for training ML models.

🛠️ Steps Performed

Data Cleaning

Removed duplicates.

Handled missing values in children, babies, agent, and company.

Dropped data leakage columns: reservation_status and reservation_status_date.

Feature Engineering

Created new features such as total_guests and is_family.

Encoded categorical variables:

One-Hot Encoding for low-cardinality features (meal, market_segment).

Frequency Encoding / Grouping for high-cardinality features (country).

Data Preparation

Split dataset into training (80%) and testing (20%) sets with stratify=y for balanced target distribution.

🎯 Target Variable

is_canceled → Binary classification (0 = Not Canceled, 1 = Canceled).

📊 Next Steps

Exploratory Data Analysis (EDA) for deeper insights.

Train and evaluate multiple ML models (Logistic Regression, Random Forest, Gradient Boosting, etc.).

Handle class imbalance with SMOTE or class weights.

Compare models using metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC.

📂 Repository Structure
Hotel_Bookings_Project/
│── data/                  # Dataset(s)
│── notebooks/             # Colab notebooks
│── hotel_bookings.csv     # Raw dataset
│── hotel_bookings_Project.ipynb  # Main notebook
│── README.md              # Project documentation

⚡ Tech Stack

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Colab Notebook

✨ Acknowledgements

Dataset: Hotel Booking Demand Dataset
