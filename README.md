🏠 House Price Prediction Dashboard
An interactive machine learning dashboard that predicts California house prices using a **Linear Regression** model. The project demonstrates the complete workflow of data preprocessing, model training, evaluation, and deployment of predictions through a clean web-based interface.
📊 Overview
This project uses the California Housing Dataset to train a Linear Regression model and visualize its performance through an interactive dashboard.
Users can:
   - View model performance metrics
   - Analyze feature importance (coefficients)
   - Explore prediction accuracy
   - Examine residual distributions
   - Generate custom house price predictions
✨ Features
📈 Model Performance Dashboard
   - Dataset statistics
   - R² Score
   - RMSE (Root Mean Squared Error)
   - Average house price
📉 Prediction Analysis
   - Predicted vs Actual Price Scatter Plot
   - Residual Distribution Histogram
   - Sample Prediction Comparison
🔍 Feature Importance
Visual representation of model coefficients showing how each feature influences house prices.
🏡 Custom Price Prediction
Enter housing characteristics and receive an estimated house price instantly.
🧠 Machine Learning Pipeline
Dataset
   California Housing Dataset
Data Preprocessing
   - Missing value handling
   - Feature scaling using `StandardScaler`
   - Train-Test Split (80/20)
Model
   - Linear Regression
Evaluation Metrics
   - R² Score: 0.908
   - RMSE: $42,102
     
📋 Features Used

|   Feature  |      Description           |
|------------|----------------------------|
| MedInc     | Median Income              |
| HouseAge   | Average House Age          |
| AveRooms   | Average Number of Rooms    |
| AveBedrms  | Average Number of Bedrooms |
| Population | Population in Block        |
| AveOccup   | Average Occupancy          |
| Latitude   | Geographic Latitude        |
| Longitude  | Geographic Longitude       |

🛠️ Technologies Used
Machine Learning
   - Python
   - Scikit-learn
   - NumPy
   - Pandas
Frontend
   - HTML5
   - CSS3
   - JavaScript
Visualization
   - Chart.js
📸 Dashboard Preview
  Main Dashboard
   - Performance Metrics
   - Scatter Plot Visualization
   - Residual Analysis
   - Feature Coefficients
  Prediction Tool
Users can adjust housing features and generate price predictions in real time.
🚀 Getting Started
-> Clone the Repository
```bash
git clone https://github.com/sssxrxhhh07/house-price-prediction-dashboard.git
cd house-price-prediction-dashboard
```
Open the Dashboard
Simply open:

```bash
house_price_prediction.html
```
in your browser.
No additional setup is required.
📊 Model Interpretation
 Positive Impact Features
   - Median Income
   - Average Rooms
   - House Age
 Negative Impact Features
   - Population
   - Average Occupancy
   - Latitude
The coefficient chart helps visualize the magnitude and direction of each feature's influence on predicted house prices.

📈 Sample Results

|     Metric     |     Value     |
|----------------|---------------|
| Dataset Size   | 2,000 Records |
| Features       | 8             |
| Missing Values | 0             |
| R² Score       | 0.908         |
| RMSE           | $42,102       |
| Average Price  | $335,000      |

 🎯 Learning Objectives
This project demonstrates:
   - Regression modeling
   - Feature scaling
   - Model evaluation
   - Data visualization
   - Interactive dashboards
   - Deploying ML insights in a web application
 🔮 Future Improvements
   - Add Random Forest Regression
   - Add XGBoost Regressor
   - Compare multiple models
   - Load predictions from CSV uploads
   - Deploy using Flask or Streamlit
   - Connect to real housing datasets
 👨‍💻 Author
Created as a Machine Learning and Data Visualization project to demonstrate end-to-end predictive analytics using Linear Regression.
