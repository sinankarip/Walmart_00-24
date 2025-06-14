Walmart Stock Price Prediction using Machine Learning
🚀 Project Overview

This project aims to predict Walmart’s stock prices between 2000 and 2004 using advanced machine learning techniques. By leveraging historical stock data, technical indicators, and external financial features, the goal is to build a robust regression model capable of forecasting future price movements with high accuracy.
📊 Dataset

    Time Period: 2000 - 2004

    Data Sources:

        Walmart daily stock prices and volumes

        Market indicators (e.g., NYSE index)

        Commodity prices (gold, silver, brent oil)

        Currency index (USD index)

    Preprocessing:

        Feature engineering with rolling statistics and volatility measures

        Time feature encoding using sinusoidal transforms for seasonality

        Missing data handling and normalization

🛠️ Modeling Approach

    Exploratory Data Analysis (EDA) to understand patterns and correlations

    Feature selection based on statistical and domain knowledge

    Use of tree-based ensemble models, especially XGBoost, for regression

    Comparison with baseline models (Linear Regression, Random Forest)

    Model tuning and cross-validation for optimal performance

📈 Results & Evaluation

    Performance metrics: RMSE, MAE, R² scores

    Analysis of feature importance highlighting key drivers

    Time series visualization comparing actual vs predicted prices

    Insights on market behavior and seasonality effects

💡 Key Learnings

    Incorporating external financial indicators improves predictive power

    Sin-Cos time encoding effectively captures seasonality in stock prices

    Feature engineering is critical to boost model accuracy in financial data

    XGBoost shows strong performance in regression tasks on stock data

🛠️ Technologies & Tools

    Python (Pandas, NumPy, Scikit-learn, XGBoost)

    Data visualization with Matplotlib and Seaborn

    Jupyter notebooks for interactive analysis and modeling
