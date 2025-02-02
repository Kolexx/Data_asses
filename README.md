**Predictive Analytics for E-commerce Sales Using Economic Indicators**

**Overview**
This project explores predictive analytics for e-commerce sales using economic indicators.
It focuses on identifying high-value transactions based on features such as GDP growth, inflation, and CPI. 
By leveraging Linear Regression and Logistic Regression, we aim to forecast total sales and classify transactions as high-value or not using a data-driven approach.

**Dataset**
The dataset consists of e-commerce transaction records, with key features such as:

**TotalSales:** Computed as Quantity × UnitPrice, representing the transaction value.
**GDP Growth, Inflation, CPI:** Economic indicators used as predictive features.
**HighValue:** A binary target variable indicating whether a transaction is high-value (1) or not (0), based on whether TotalSales exceeds the median transaction value.

**Project Workflow**
Data Preprocessing

Removed unnecessary columns (InvoiceNo, StockCode, CustomerID, etc.).
Created new features (TotalSales, HighValue).
Handled missing values and outliers.
Exploratory Data Analysis (EDA)

Examined data distributions and correlations.
Visualized trends in TotalSales and economic indicators.
Predictive Modeling

Linear Regression: Predicts TotalSales using economic indicators.
Logistic Regression: Classifies transactions as high-value or not.
K-Nearest Neighbors (KNN): Explored as an alternative model.
Model Evaluation

Regression: Evaluated using Mean Squared Error (MSE) and R² score.
Classification: Assessed using accuracy, precision, recall, and F1-score.
Results
Linear Regression effectively predicts TotalSales, though external market factors may influence performance.
Logistic Regression achieves reasonable accuracy in classifying high-value transactions.
Feature importance analysis suggests economic indicators contribute to sales prediction, but additional factors (e.g., seasonal trends, marketing efforts) could improve accuracy.
Future Improvements
Integrating additional macroeconomic variables (e.g., exchange rates, interest rates).
Exploring advanced machine learning models like Random Forest and XGBoost.
Implementing time-series forecasting for trend analysis.

**How to Run the Project**
**Clone the repository:** git clone https://github.com/Kolexx/Data_asses.git
cd Data_asses
**Install dependencies:** pip install -r requirements.txt

Author

Korede Solomon Odeyemi

MSc Computer Science, 

University of Law, London

