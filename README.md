**Competitions held by Analytics Vidhya**

**Time Series**

**Click Prediction**

1.  **Amex 2018** - Build a model to predict the probability of the next page a
    user will visit.

    1.  **Metrics**: AUC ROC

    2.  **Models used:** CatBoost and Light GBM

    3.  **Approach:**

        1.  Created new feature such as counts, number of times a user visited a
            page, how long since his last visit, mean encoded features against
            the target variable, etc

        2.  Tuned hyperparameters using RandomSearch and selected features using
            forward feature selection method.

        3.  Trained a **CatBoost** and **LightGBM** model.

**Demand Forecasting**

1.  **Food Demand Forecasting** - Predict 10 weeks out demand for meals.

    1.  **Metrics**: Root of Mean Squared Logarithmic Error (RMSLE)

    2.  **Models used**: RandomForestRegressor and XGBoost

    3.  **Approach**:

        1.  Build many interaction features and statistical features such as
            sum, count, min, max, mean and mode. Dropped non-correlated
            features.

        2.  Trained a RandomForestRegressor and XGBoost model.
