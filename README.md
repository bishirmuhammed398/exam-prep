# exam-prep
Act as a machine learning expert.

Solve the following regression problem using Python and Scikit-learn. Follow a structured ML workflow similar to a professional ML project.

Steps to follow:

1. **Library Imports**

   * Import necessary libraries such as numpy, pandas, matplotlib, seaborn, sklearn.

2. **Load Dataset**

   * Load the dataset and display shape, head, columns, info, and description.

3. **Data Cleaning**

   * Check and remove duplicates
   * Check and handle missing values
   * Drop unnecessary columns if needed

4. **Feature Engineering**

   * Create useful features if applicable
   * Convert categorical variables properly

5. **Exploratory Data Analysis (EDA)**

   * Distribution plot of the target variable
   * Scatter plots for important relationships
   * Correlation heatmap for numerical variables

6. **Outlier Detection and Handling**

   * Use IQR method for numerical columns
   * Remove extreme outliers

7. **Encoding**

   * Convert categorical variables using one-hot encoding or label encoding

8. **Train-Test Split**

   * Split dataset into training and testing sets (80/20)

9. **Feature Scaling**

   * Apply StandardScaler where necessary

10. **Model Development**
    Train at least two regression models:

    * Linear Regression
    * Random Forest Regressor

11. **Model Evaluation**
    Evaluate using:

    * R² Score
    * Mean Absolute Error (MAE)
    * Mean Squared Error (MSE)

12. **Hyperparameter Tuning**

    * Use RandomizedSearchCV for Random Forest

13. **Model Comparison**

    * Create a comparison table showing model performance

14. **Model Saving**

    * Save the best model using pickle
    * Save the scaler as well

Write clean, well-commented Python code for each step.
