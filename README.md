**Project Overview**

This project involves building a machine learning pipeline to analyze and forecast sales for restaurants and stores. Using historical sales data, we predict future sales trends, identify key drivers of sales, and provide actionable insights for decision-making.

Key objectives of the project:

Forecast future sales for the next year using machine learning models.
Analyze key factors influencing sales, such as seasonal trends and item popularity.
Develop a scalable and interpretable forecasting pipeline.

**Methodology**

Data Preprocessing:

Handled missing values and cleaned data.
Extracted date-based features (e.g., year, month, quarter).
Scaled numeric features for use in machine learning models.

Exploratory Data Analysis (EDA):

Identified seasonal patterns and trends in sales.
Explored relationships between sales and features such as price and item_count.

Model Development:

Implemented the following machine learning models:
Linear Regression,
Random Forest,
XGBoost and
LSTM (for time-series modeling)

Evaluated models using metrics like Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Percentage Error (MAPE).

Forecasting:

Generated future data for one year and predicted sales using the best-performing models.

**Key Results**

Best Model: Random Forest

MSE: 59.91,
R²: 94.43

XGBoost Performance:

MSE: 78.05,
R²: 90.55

The models successfully captured seasonal trends and provided accurate sales forecasts.
