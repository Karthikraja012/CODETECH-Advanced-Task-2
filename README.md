# CODETECH-Advanced-Task-2
---

### Project Overview: Salary Prediction using Linear Regression

**Project Title:** Salary Prediction using Linear Regression

**Name:** Karthik Raja N  
**Company:** CODETECH IT SOLUTIONS  
**ID:** CT0806AQ  
**Domain:** Data Analytics  
**Duration:** Dec 2024 to Jan 2025

**Project Description:**
This project focuses on building a linear regression model to predict the salary of an individual based on their years of experience. The objective is to establish a clear understanding of how work experience influences salary and to develop a predictive model that can estimate salaries for new data points.

**Objective:**
- To analyze the relationship between years of experience and salary.
- To build a simple linear regression model for salary prediction.
- To evaluate the model’s performance and visualize the predictions.

**Dataset Description:**
- **Columns:**
  - `YearsExperience`: Numeric, representing the number of years of work experience.
  - `Salary`: Numeric, representing the salary corresponding to the years of experience.
- **Source:** [Mention the source if applicable]

**Project Phases:**
1. **Data Collection and Exploration:**
   - Load the dataset.
   - Perform Exploratory Data Analysis (EDA) to understand the data distribution and identify any patterns or anomalies.
2. **Data Preprocessing:**
   - Split the data into training and testing sets using Scikit-learn’s `train_test_split` function.
   - Normalize or standardize the data if necessary (though not strictly required for simple linear regression).

3. **Model Development:**
   - Develop a linear regression model using Scikit-learn’s `LinearRegression` class.
   - Fit the model on the training data.

4. **Model Evaluation:**
   - Evaluate the model on the test data using metrics such as Mean Squared Error (MSE) and R² score.
   - Predict the salaries for the test set and compare them with the actual values.

5. **Visualization:**
   - Use Seaborn’s `regplot` to visualize the actual vs. predicted salaries along with the regression line.
   - Include a matplotlib plot to enhance the visual interpretation of the model's performance.

**Conclusion:**
The project successfully demonstrates the application of linear regression to predict salaries based on years of experience. The final model, along with visualizations, provides insights into the linear relationship between these two variables, making it a useful tool for HR analytics and salary forecasting.

---

