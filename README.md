# House Price Prediction Using PySpark

This project aims to predict U.S. house prices using Zillow’s Home Value Index (ZHVI) dataset. It demonstrates the full data science workflow — from preprocessing and exploratory analysis to machine learning model building — all done at scale with PySpark.  It was developed for DSCI 632 at Drexel University.

## Files Included

- `DSCI632_Final_Report.ipynb`: Main Jupyter notebook with code for data processing, analysis, and modeling.
- `House_Price_Prediction_DSCI632_FinalReport.pdf`: Final summary report with explanations and visualizations.
- `cleaned_data.csv`: Cleaned dataset used for modeling.
- `Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv`: Original Zillow dataset (full raw data).

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

---

*This project was developed as part of DSCI 632 at Drexel University (Winter 2024).*
