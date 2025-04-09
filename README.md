# House Price Prediction Using PySpark

This project aims to predict U.S. house prices using Zillow’s Home Value Index (ZHVI) dataset. It demonstrates the full data science workflow — from preprocessing and exploratory analysis to machine learning model building — all done at scale with PySpark.

## Project Structure

- `notebooks/DSCI632_Final_Report.ipynb`: Main Jupyter notebook (PySpark-based).
- `reports/House_Price_Prediction_DSCI632_FinalReport.pdf`: Final summary report.
- `data/cleaned_data.csv`: Preprocessed dataset used for modeling.
- `data/Metro_zhvi_...csv`: Original Zillow dataset (optional, or linked below).

## Key Highlights

- Real-world Dataset: Zillow Home Value Index (ZHVI), with monthly data from 2000 to 2024 across U.S. regions.
- Big Data Tools: Entire project built using Apache Spark (PySpark).
- EDA Insights:
  - Home prices increased consistently since 2000.
  - Urban homes cost approximately 45% more than rural homes.
  - Seasonal price peaks occur during summer months.
- Modeling:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Best Model: Gradient Boosting Regressor  
  - RMSE: 94,468  
  - MAE: 58,686  
  - R²: 0.2712

## Requirements

Install the required packages using pip:

```bash
pip install pyspark pandas matplotlib scikit-learn
