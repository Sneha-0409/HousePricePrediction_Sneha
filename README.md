### 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview:
This project aims to predict house prices based on various property features such as area, number of bedrooms, bathrooms, parking spaces, location preferences, and amenities. The dataset was cleaned, preprocessed, and analyzed using Python, followed by the implementation of Machine Learning models to estimate property prices.

## 📊 Dataset
The dataset contains information about residential properties, including:
1. Area
2. Bedrooms
3. Bathrooms
4. Stories
5. Parking
6. Main Road Access
7. Guest Room
8. Basement
9. Hot Water Heating
10. Air Conditioning
11. Preferred Area
12. Furnishing Status
13. Price (Target Variable)

## Data Preprocessing:
1. Checked for missing values and duplicates
2. Performed exploratory data analysis (EDA)
3. Applied One Hot Encoding (OHE) to categorical features
4. Split the data into training and testing sets (80:20)

## Models Used:
1. Linear Regression
2. Random Forest Regressor

## Results:
1. Model- Linear Regression, MAE - 873, R² - 450, Score - 0.63	
2. Model- Random Forest Regressor, MAE - 875, R² - 147, Score -	0.52

### Linear Regression performed better on this dataset, explaining approximately 63% of the variation in house prices.

## Visualizations:
1. Price Distribution Histogram
  <img width="619" height="415" alt="Screenshot 2026-06-19 at 22 15 22" src="https://github.com/user-attachments/assets/7481e9fb-ec32-41a9-89a2-6a77f066dac0" />
2. Correlation Heatmap
<img width="587" height="582" alt="Screenshot 2026-06-19 at 22 15 55" src="https://github.com/user-attachments/assets/3d4adb81-be1e-455f-befe-e7b525dc21aa" />
3. Actual vs Predicted Price Scatter Plot
<img width="538" height="621" alt="Screenshot 2026-06-19 at 22 16 06" src="https://github.com/user-attachments/assets/8bad6809-4513-4784-beae-30e843b586e0" />

## 🔍 Key Insights:
1. Area was the most influential feature affecting house prices.
2. Bathrooms, stories, parking, and air conditioning also had a significant impact.
3. Properties located in preferred areas generally commanded higher prices.
4. Amenities play an important role in determining property value.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

## 📁 Repository Structure

```text
HousePricePrediction/
│
├── HousePricePrediction.ipynb
├── Housing.csv
├── summary.pdf
├── analysis.ipynb.pdf
│
└── Charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

## 👩‍💻 Author
Sneha- 
B.Tech CS, MITS-DU Gwalior
