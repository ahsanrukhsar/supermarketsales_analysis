**Data Loading:**

The dataset is loaded into a DataFrame using Pandas. The first and last 10 rows of data are displayed to understand the structure.
**Data Information:**

Columns and data types of the DataFrame are explored using .columns and .dtypes methods.
The 'Date' column is converted to a datetime object and set as the index for easier time-series analysis.
The .describe() method is used to generate descriptive statistics.
**Univariate Analysis:**

*Distribution of Customer Ratings:*
A distribution plot of the Rating column is created using Seaborn. Mean and percentile lines are added for further insight.
Histograms are plotted for all numeric columns to visualize their distributions.
Branch Sales Analysis:

A count plot for branches (Branch column) and payment methods (Payment column) is created to compare the frequency of sales across branches and payment methods.

**Bivariate Analysis:**

A regression plot (using Seaborn) is used to examine the relationship between Rating and gross income.
Boxplots are created to show how gross income varies across different branches and genders.

**Time-Series Analysis:**

A time series plot is used to visualize the trend of gross income over time. The data is grouped by date, and the average gross income per day is calculated.

**Duplicate and Missing Data Handling:**

Duplicates in the dataset are identified using .duplicated() and dropped using .drop_duplicates().
Missing values are handled by filling them with the mode (most frequent value) of the respective columns using .fillna().# supermarketsales_analysis
Supermarket sales data analysis using python libraries
