This project analyzes sales data to extract meaningful insights regarding profitability, customer behavior, and the impact of discounts across different regions.

Data Cleaning and Preprocessing
Handling Missing Values: Identified and addressed missing data.
Outlier Detection and Removal: Interquartile Range (IQR) was used to detect and remove outliers.
Normalization and Standardization: Ensured data was appropriately scaled for analysis.
Descriptive Statistics
Summary Statistics: Calculated mean, median, standard deviation, and kurtosis for numerical variables.
Data Distribution Analysis: Visualized distributions with histograms, boxplots, and density plots. Checked for skewness and kurtosis.
Correlation Analysis
Pearson Correlation: Initially considered for numerical variables but found unsuitable due to non-normal distribution.
Spearman Correlation: Used to assess monotonic relationships. Key Insight: Found a strong negative correlation between discount levels and profit margins.
Analysis of Variance (ANOVA)
One-Way ANOVA: Analyzed the difference in profit across regions and random regional groups.
Conducted normality checks (QQ plots, Shapiro-Wilk test) and homogeneity of variance (Levene's test).
Result: Determined whether there were statistically significant differences in mean profits among different regions.
Kruskal-Wallis Test
Non-parametric Test: Used since data did not meet ANOVA assumptions.
Result: Analyzed differences in profit medians across regions.
Profitability and Regional Analysis
Top and Bottom Cities by Profit: Identified cities with the highest and lowest profit margins.
Regional Profitability: Compared total profits across different regions. Analyzed monthly profit trends to understand seasonality.
Impact of Discounts on Profit
Discount and Profit Relationship: Analyzed the impact of discount levels on profit margins.
Key Insight: Found a significant negative correlation between higher discounts and lower profits.
Shipping Cost Analysis
Cities with Highest and Lowest Shipping Costs: Identified cities with varying shipping costs.
Average Shipping Cost: Compared shipping costs across cities.
Customer Analysis
Number of Customers by City: Analyzed customer distribution across cities.
Customer Segmentation: Grouped customers based on regions and categories.
Product Analysis
Top-Selling Products: Identified products with the highest sales volumes.
High vs. Low Margin Products: Differentiated between products with high and low profit margins.
