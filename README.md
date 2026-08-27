# Hotel Booking Data Analysis – Day 15

## Overview

This project performs a complete end-to-end Exploratory Data Analysis (EDA) on a large hotel booking dataset using Python, Pandas, Matplotlib, and Seaborn.

The analysis follows a complete data science workflow, starting with data-quality assessment and preprocessing, followed by statistical analysis, visualization, business insights, and management recommendations.

## Dataset

- **Original Records:** 25,180
- **Records After Cleaning:** 25,000
- **Original Columns:** 35
- **Additional Derived Columns:** Created during preprocessing

## Data Quality Analysis

The dataset was examined for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values
- Invalid numeric values
- Outliers

### Data Preprocessing

The following preprocessing techniques were applied:

- Converted date columns to datetime format
- Removed duplicate records
- Standardized categorical values
- Filled appropriate numeric missing values using median imputation
- Filled selected categorical missing values using mode imputation
- Removed invalid negative numeric values
- Detected and capped extreme outliers using the IQR method
- Created useful derived variables such as total guests and stay type

## Exploratory Data Analysis

The analysis includes:

- Descriptive statistics
- Univariate analysis
- Bivariate analysis
- Group-wise analysis
- Hotel-type comparison
- Market-segment analysis
- Cancellation analysis
- Lead-time analysis
- ADR and revenue analysis
- Customer satisfaction analysis
- Correlation analysis

## Visualizations

The notebook contains several Matplotlib and Seaborn visualizations, including:

- Cancellation count plots
- Lead-time distribution histogram
- ADR box plots
- Satisfaction violin plots
- Market-segment cancellation bar charts
- Hotel-type revenue comparison
- Lead-time vs cancellation scatter plot
- ADR vs estimated revenue scatter plot
- Correlation heatmap

## Key Business Insights

1. The dataset shows a high overall cancellation rate, making cancellation management an important business priority.
2. Longer booking lead times are associated with increased cancellation risk.
3. Resort Hotels show stronger commercial performance in terms of ADR and estimated revenue compared with City Hotels.
4. Online Travel Agency bookings show particularly high cancellation rates.
5. Revenue performance is strongly connected to pricing and stay-related factors.

## Management Recommendations

1. Introduce stronger cancellation controls for long-lead bookings.
2. Develop market-segment-specific cancellation policies.
3. Closely monitor Online Travel Agency bookings.
4. Maintain premium pricing strategies for high-value hotel segments.
5. Use ADR, stay duration, lead time, and cancellation probability together for revenue-management decisions.
6. Establish regular dashboards for revenue, cancellation, ADR, and customer satisfaction KPIs.
7. Strengthen data-quality validation at the point where booking data is entered.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Project Files

- `Day15_Hotel_Booking_Complete_EDA.ipynb` – Complete EDA notebook
- `Day15_Hotel_Booking_Executive_EDA_Report.docx` – Executive-ready EDA report
- `Day15_Executive_Hotel_Booking_EDA_Dataset.csv` – Hotel booking dataset

## How to Run

1. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
2. Upload the hotel booking CSV dataset when prompted.
3. Run the notebook cells from top to bottom.
4. Review the data-quality analysis, visualizations, insights, and recommendations.
5. Upload the notebook, report, and dataset to the GitHub repository.

## Conclusion

The analysis highlights cancellation risk, booking lead time, hotel type, market segment, pricing, and revenue as important factors in hotel booking performance. The findings can support better cancellation policies, revenue management, pricing decisions, and data-driven operational planning.
