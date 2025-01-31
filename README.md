# California-Housing-Regression-Project
This project uses machine learning to predict house prices in California based on various features like the median income, house age, and population. We apply different regression techniques and compare their performances.
**What’s Inside**

## In this project, we:

### 1. **Preprocessing the Data**
   - Clean up any missing values.
   - Handle outliers using appropriate techniques.
   - Scale the features to normalize the data for model training.

### 2. **Training Different Models**
   We trained the following regression models to predict house prices:
   - **Linear Regression**
   - **Decision Tree Regressor**
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
   - **Support Vector Regressor (SVR)**

### 3. **Evaluating the Models**
   We evaluated each model using the following metrics:
   - **Mean Squared Error (MSE)**
   - **Mean Absolute Error (MAE)**
   - **R² Score** (Coefficient of Determination)

## Results

| Model                        | MSE    | MAE    | R²     |
|------------------------------|--------|--------|--------|
| **Linear Regression**         | 0.3310 | 0.4324 | 0.6681 |
| **Decision Tree**             | 0.3360 | 0.3966 | 0.6630 |
| **Random Forest**             | 0.1715 | 0.2871 | 0.8280 |
| **Gradient Boosting**         | 0.2029 | 0.3288 | 0.7965 |
| **SVR**                       | 0.2088 | 0.3326 | 0.7906 |

## Conclusion

- **Random Forest Regressor** was the top performer, with the best results across all metrics.
- **Decision Tree Regressor** performed the worst, with the highest MSE and lowest R².
