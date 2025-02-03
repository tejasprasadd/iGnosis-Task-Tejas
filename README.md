# Retail Analysis

This script performs a retail analysis using Python with the Pandas and Tabulate libraries. It analyzes transaction and purchase behavior data to identify key trends and insights.

## Dependencies

- pandas
- tabulate

You can install these libraries using pip:

```bash
pip install pandas tabulate
```
## Data Files

The script requires two CSV files as input:

- `transaction_data.csv`: Contains transaction details such as product information, sales, and dates.
- `purchase_behaviour.csv`: Contains customer demographics and loyalty card information.

Place these files in the same directory as the script or provide the correct file paths in the script.  The current script assumes the files are in the `/content/` directory which is common for Google Colab. You'll likely need to change this path.

## Script Description

The Python script (`retail_analysis.py` - or whatever you name it) performs the following analyses:

1. **Top 3 Bestselling Products:** Identifies and displays the top 3 bestselling products based on total sales.

2. **Monthly Sales Trends:** Shows the monthly sales trends for the top-selling products.

3. **High-Value Customer Identification:** Identifies high-value customers based on their total spending (top 20%).

4. **Segment Analysis:** Analyzes the spending behavior of high-value customers based on their lifestage and premium customer status.

5. **Product Preference by Top Segments:** Determines the preferred products for the identified customer segments.

6. **Customer Type Distribution:** Shows the distribution of customer types based on lifestage and premium customer status.
