## Overview
This project, created as an assignment for COS 472 by Josh Thyng, analyzes the nutritional information of McDonald's menu items. It focuses on building regression models to predict nutritional values and evaluate relationships within the data. The project leverages linear and logistic regression techniques, as well as various performance metrics to assess model accuracy.

## Dataset
The dataset used is the **McDonald's Menu** dataset, which contains detailed nutritional information for various items. Key columns include:
- Category (e.g., Breakfast, Dessert)
- Item Name
- Serving Size
- Calories
- Total Fat, Saturated Fat, and other fat metrics
- Carbohydrates, Sugars, and Dietary Fiber
- Protein and Vitamin content

The data provides insights into the nutritional breakdown of McDonald's food items, supporting regression models to explore the impact of serving size and item type on calorie and macronutrient content.

## Notable Features
1. **Linear Regression on Calories**: The project uses linear regression to predict calorie content based on serving size and other nutritional values.
2. **Logistic Regression for Classification**: A logistic regression model is applied to classify items based on nutritional thresholds.
3. **Data Visualization**: The project includes visualizations for calorie distribution, fat content, and other nutritional factors across menu items.

## Packages Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **scikit-learn**: For machine learning models, including:
  - `LinearRegression` for regression analysis.
  - `LogisticRegression` for classification tasks.
  - Model evaluation metrics such as `accuracy_score`, `precision_score`, `recall_score`, and `f1_score`.
- **Seaborn and Matplotlib**: For data visualization, offering insights into data distribution and model predictions.

## Files
- `assignment_2_472.ipynb`: The main Jupyter notebook containing code, analysis, and visualizations.

## How to Run
1. Ensure all required packages are installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
