# House Price Prediction Using Python

This project implements the full data science workflow to predict house prices. It covers everything from data exploration and preprocessing to model evaluation and hyperparameter tuning. The primary goal is to understand the key factors influencing house prices and build accurate predictive models.

---

## 📖 **Overview**
The project leverages Python to handle various stages of the data science process:
- **Data Exploration:** Analyzed features like median age, total rooms, and ocean proximity to gain insights.
- **Feature Engineering:** Created new variables such as bedroom ratio and household rooms for better predictions.
- **Modeling:** Built and compared linear regression and random forest models to predict house values.
- **Hyperparameter Tuning:** Systematically adjusted parameters to optimize model performance.
- **Evaluation:** Used metrics like R² score to assess model accuracy.

---

## 🛠️ **Technologies Used**
- **Programming Language:** Python  
- **Libraries and Tools:**
  - Data Analysis: `Pandas`, `NumPy`
  - Data Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-learn`

---

## 📊 **Steps Followed**

### 1. **Data Exploration**
- **Objective:** Understand the data, identify patterns, and detect anomalies.  
- **Methods Used:** 
  - Summary statistics
  - Visualizations (scatter plots, heatmaps)

### 2. **Feature Engineering**
- Created derived features such as:
  - `Bedroom Ratio = Bedrooms / Total Rooms`
  - `Household Rooms = Total Rooms / Households`

### 3. **Model Building**
- Models implemented:
  - **Linear Regression**: For baseline predictions.
  - **Random Forest**: For capturing non-linear relationships.

### 4. **Hyperparameter Tuning**
- Tuned hyperparameters using GridSearchCV to improve Random Forest performance.

### 5. **Model Evaluation**
- Evaluated models using:
  - R² score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## 💡 **Key Insights**
- Feature engineering significantly improved model accuracy by incorporating domain-specific knowledge.
- Random forest outperformed linear regression in capturing complex relationships between features and target.
- Visualizations like heatmaps helped identify strong correlations between features, enhancing feature selection.

---

## 📈 **Results**
- Achieved a high R² score with optimized Random Forest.
- Models demonstrated the importance of location and proximity to amenities in predicting house prices.

---

## 🔗 **How to Run This Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/nisch-mhrzn/House_Prediction.git
   ```
2. Install the required libraries:
   ```bash
   pip install scikit-learn pandas numpy seaborn matplotlib
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook House_Prediction.ipynb
   ```

---

## 🙌 **Contributions**
Contributions are welcome! Feel free to fork this repository and submit a pull request.

---
