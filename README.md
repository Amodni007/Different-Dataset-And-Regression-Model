# Different-Dataset-And-Regression-Model
# Rent Classifieds EDA

## 📌 Objective
Perform exploratory data analysis (EDA) on apartment rental listings to uncover patterns in rent prices based on apartment size, number of bedrooms, pet policy, and photo availability.

## 📊 Dataset
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified/)

## 💡 Questions Answered
- What is the relationship between apartment size and rent?
- How does rent vary with the number of bedrooms?
- What is the average rent for 1-bed, 2-bed, and 3-bed apartments?
- Does including a photo affect rent?
- How does rent compare for pet-friendly vs non-pet listings?

## 🛠 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## 🔍 Key Insights
- Rent increases with apartment size and number of bedrooms.
- Listings with photos had slightly higher average rent.
- Pet-friendly apartments generally had higher rent than non-pet-friendly ones.
# Calgary Traffic Incidents EDA

## 📌 Objective
Analyze traffic incidents in Calgary to identify patterns in timing, location, and seasonality.

## 📊 Dataset
Source: [City of Calgary Open Data Portal](https://data.calgary.ca/Transportation-Transit/Traffic-Incidents/35ra-9556)

## 💡 Questions Answered
- Which neighborhoods report the most traffic incidents?
- At what time of day are incidents most common?
- Are there seasonal trends in incident frequency?

## 🛠 Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## 🔍 Key Insights
- Certain neighborhoods have significantly higher incident counts.
- Incidents peak during morning and evening rush hours.
- Winter shows a spike in incidents, likely due to snow and ice conditions.

# Gas Turbine Emissions – Regression Analysis

## 📌 Objective
Build machine learning models to predict CO and NOx emissions from gas turbine sensor readings using regression techniques.

## 📊 Dataset
Source: [UCI Gas Turbine and Emission Data Set](https://archive.ics.uci.edu/dataset/551/gas+turbine+co+and+nox+emission+data+set)
Files used:
- gt_2011.xlsx to gt_2015.xlsx (merged)

## 🧠 Models Built
- Linear Regression (to predict CO)
- Random Forest Regressor (to predict NOx)

## 🛠 Tools Used
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## 🔍 Key Findings
- Linear Regression provided a reasonable baseline for CO predictions.
- Random Forest outperformed other models in predicting NOx with higher R² and lower RMSE.
- Visual plots confirm model fit with real-world emission data.

## 📁 Output
Final merged dataset: `gas_turbine_data.xlsx`
