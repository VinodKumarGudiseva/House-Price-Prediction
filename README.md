House Price Prediction

Project Overview

This project focuses on predicting house prices using Machine Learning regression techniques. The objective is to analyze various property features and build predictive models that estimate house prices accurately. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and visualization.

Dataset

The dataset used in this project is the Housing Prices Dataset from Kaggle.

Features include:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

Target Variable:

- Price

Project Tasks

Task 1: Data Loading & Exploration

- Loaded the dataset using Pandas
- Displayed dataset samples
- Checked dataset dimensions
- Identified features and target variable
- Verified missing values

Task 2: Data Cleaning

- Checked and removed duplicate records
- Converted categorical variables into numerical format using One-Hot Encoding
- Prepared data for model training

Task 3: Model Building

Two regression models were implemented:

1. Linear Regression
2. Random Forest Regressor

The dataset was split into training and testing sets using an 80:20 ratio.

Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Model Performance

Model| MAE| RMSE| R² Score
Linear Regression| 970,043| 1,324,507| 0.653
Random Forest Regressor| 1,021,546| 1,400,566| 0.612

Best Performing Model

Linear Regression achieved the highest R² Score and lower prediction errors, making it the best-performing model for this dataset.

Visualizations

The project includes the following visualizations:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted Price Scatter Plot

All generated charts are available in the "charts" folder.

Key Findings

The most influential features affecting house prices were:

1. Bathrooms
2. Air Conditioning
3. Hot Water Heating
4. Preferred Area
5. Furnishing Status
6. Stories
7. Basement
8. Main Road Access
9. Guest Room
10. Parking

The analysis showed that amenities, location-related factors, and property structure significantly impact house prices.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Project Structure

HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png

Conclusion

This project successfully demonstrates the application of Machine Learning techniques for house price prediction. Linear Regression provided the best results on the given dataset, explaining approximately 65% of the variation in house prices. The findings highlight the importance of property amenities, location, and structural characteristics in determining housing prices.

Author

Vinod Kumar Gudiseva

B.Tech – Artificial Intelligence & Machine Learning

Nalla Narasimha Reddy Group of Institutions
