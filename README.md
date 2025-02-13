# Pizza Sales Data Analysis

This repository contains the analysis of a dataset detailing pizza sales. The goal of this project is to explore the relationship between the price per pizza and the quantity sold, as well as to visualize key insights from the data. The analysis aims to help understand patterns in sales, optimize pricing strategies, and make data-driven decisions.

## Project Overview

The dataset used in this analysis contains the following columns:
- **unit_price**: The price per pizza (in dollars).
- **quantity**: The number of pizzas sold.

## Key Analysis and Insights

1. **Scatter Plot - Price vs Quantity Sold**:
   - A scatter plot was initially created to visualize the relationship between the price per pizza and the quantity sold. However, the scatter plot didn’t provide clear insights due to overlapping points or a potential non-linear relationship.
   
2. **Alternative Visualizations**:
   - **Bar Plot**: A bar plot was suggested to compare quantities for different price ranges.
   - **Line Plot**: A line plot was considered for time series or ordered data to show trends in price vs. quantity.
   - **Box Plot**: A box plot was proposed to visualize the distribution of quantities sold at various price points.
   - **Violin Plot**: A violin plot was suggested to show the density and distribution of quantities sold per price point, combining aspects of both box plots and density plots.
   - **Heatmap**: A heatmap could be used to visualize the correlation between different variables (such as price and quantity).

## Files Included

- **pizza_sales.csv**: The main dataset containing information about the pizza prices and quantities sold.
- **Analysis Scripts**: Code used for exploratory data analysis (EDA), visualizations, and statistical analysis (TBD).

## Future Analysis

- **Correlation Analysis**: A deeper dive into the correlation between price and quantity sold.
- **Trend Analysis**: If the dataset includes time-related data, identifying any seasonal or time-based trends.
- **Sales Optimization**: Using regression or machine learning models to predict optimal pricing strategies based on quantity sold.
  
## Getting Started

To run the analysis on this project locally, clone the repository and follow the instructions below.

### Prerequisites

- Python 3.x
- Required libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `numpy`

You can install the required libraries using `pip`:

```bash
pip install pandas matplotlib seaborn numpy
```

### Running the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd pizza-sales-analysis
   ```
3. Run the analysis scripts (e.g., `pizza_sales_analysis.py`):
   ```bash
   python pizza_sales_analysis.py
   ```

## Conclusion

This analysis aims to provide valuable insights into how the price of pizzas impacts sales quantity. Further analysis and visualizations will be added to explore the data more deeply and optimize pizza sales strategies.
