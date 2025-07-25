🎬 Movie Rating Prediction using Machine Learning
https://colab.research.google.com/drive/13teRbaK0DKpkFto3fUdiWpzCiNpt8k0h?usp=sharing

This project builds a regression model that predicts the rating of Indian movies based on features such as Genre, Director, and Runtime, using machine learning techniques.

📂 Dataset
The dataset used is IMDb Movies India.csv, which includes:

Genre: Type of movie (Action, Drama, etc.)

Director: Name of the director

Duration: Movie length (converted to minutes)

Rating: IMDb rating (target)

🧠 Objective
Predict IMDb movie ratings based on categorical and numerical features, using a regression model trained on historical Indian movie data.

🔧 Technologies Used
Python (Google Colab)

Pandas, NumPy – data analysis

Scikit-learn – machine learning pipeline

Matplotlib, Seaborn – visualizations

🚀 Key Steps
Data Cleaning

Cleaned the Duration column to extract numeric values (e.g., from "120 min" to 120).

Removed missing or invalid values.

Feature Engineering

Converted Genre and Director to numeric using OneHotEncoding.

Kept Runtime as a numeric feature.

Model Building

Used a Random Forest Regressor for predicting ratings.

Wrapped everything in a Pipeline for cleaner preprocessing and training.

Evaluation

Metrics used:

R² Score – measures accuracy

RMSE – Root Mean Squared Error

Plotted Actual vs Predicted Ratings using Seaborn.

📊 Results (Sample)
✅ R² Score: ~0.60 (varies by subset)

✅ RMSE: ~0.6–0.8

✅ Visual plot for error distribution

📁 Outputs
Trained model

Evaluation metrics

Predicted vs Actual ratings plot

(Optional) CSV export of predictions

📌 How to Run
Open the Colab notebook 🔗

Upload your IMDb Movies India.csv file when prompted.

Run all cells to preprocess, train, and evaluate the model.

Review the R² score, RMSE, and scatter plot of predictions.

