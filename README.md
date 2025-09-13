# house-price-prediction-linear-regression
#Description

Predict house prices using Linear Regression on the Boston Housing Dataset.
All features except the target MEDV are used to train the model. The project includes:

Feature engineering: Prepare and transform features to improve predictions.

Data visualization: Scatter plots of predicted vs actual prices, regression line, and ideal line (y=x).

Model evaluation: Metrics include R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

Optional outlier handling: Filter extreme values to improve visualization and analysis.

This project is ideal for learning regression modeling, evaluation metrics, and feature visualization in Python.

#Dataset
The dataset used is the Boston Housing Dataset.
#Features used:
All columns except MEDV (example: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT)
#Target:
MEDV – Median value of owner-occupied homes in $1000s
#File location:
data/housing.csv

#Installation

# Clone the repo
git clone https://github.com/moonmido/house-price-prediction-linear-regression.git
cd house-price-prediction-linear-regression

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

#Results
Example metrics (your results may vary):

R²: 0.65

MAE: 3.23

RMSE: 5.07

#License
This project is open-source and free to use under the MIT License.
