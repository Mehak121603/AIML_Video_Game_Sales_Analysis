# AIML Video Game Sales Analysis

This project analyzes video game sales data using Python, pandas, scikit-learn, and visualization libraries. It includes exploratory data analysis (EDA), feature engineering, regression modeling, and clustering to gain insights into the factors affecting global video game sales.

## Features

- **Data Loading & Cleaning:** Loads and preprocesses the `vgsales.csv` dataset.
- **Exploratory Data Analysis:** Visualizes sales by genre, platform, and region.
- **Feature Engineering:** Handles missing values, encodes categorical variables, and creates new features.
- **Regression Modeling:** Predicts global sales using Linear Regression and Random Forest.
- **Clustering:** Groups games by engagement metrics using KMeans.
- **Model Saving:** Saves the trained Random Forest model for future use.

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib
- (Optional) xgboost

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib xgboost
```

## Usage

1. **Clone or Download the Repository**
2. **Place `vgsales.csv` in the project directory.**
3. **Open `AIML_Video_Game_Sales_Analysis (2).ipynb` in Jupyter Notebook or VS Code.**
4. **Run the notebook cells sequentially.**

## Project Structure

```
AIML_Video_Game_Sales_Analysis/
│
├── AIML_Video_Game_Sales_Analysis (2).ipynb
├── vgsales.csv
└── rf_videogame_sales_model.joblib   # Generated after running the notebook
```

## Results

- Visualizations of top genres and platforms by sales.
- Regression model performance (R² and MSE).
- Feature importance analysis.
- Engagement clustering and visualization.

## Notes

- The dataset `vgsales.csv` is required to run the analysis.
- The notebook is self-contained and does not require a backend server.

## License

This project is for educational purposes.
