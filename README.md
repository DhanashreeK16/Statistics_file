Statistical Analysis Using Python
Project Overview
This project performs statistical analysis on the Petrol Consumption dataset using Python in Jupyter Notebook. The objective is to understand the distribution of the data, identify outliers, measure relationships between variables, and draw statistical conclusions using descriptive statistics, confidence intervals, and hypothesis testing.

Dataset
The dataset contains the following variables:

Petrol Tax
Average Income
Paved Highways
Population Driver Licence (%)
Petrol Consumption
Tools & Libraries
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
SciPy
Analysis Performed
Descriptive Statistics (Mean, Median, Mode)
Skewness Analysis
Outlier Detection and Removal
Standard Deviation
Variance
Correlation Analysis
Percentile Analysis
Confidence Interval (95%)
Hypothesis Testing
Key Findings
Descriptive Statistics
The average Petrol Tax was 7.67, while Petrol Consumption had an average value of 576.77. Paved Highways recorded the highest average (5565.42), indicating considerable variation among different states. The comparison of mean and median showed that most variables follow a fairly balanced distribution with slight positive skewness.

Skewness Analysis
Most numerical variables showed positive (right) skewness, meaning their mean values were slightly higher than their median values. This indicates that a few higher observations influenced the overall distribution, while Average Income remained nearly symmetric.

Outlier Analysis
Outliers were identified using boxplots and removed through Python code. After cleaning, the dataset was reduced from 48 observations to 42 observations, resulting in a more reliable dataset for statistical analysis.

Statistical Metrics
Paved Highways showed the highest variability with the largest standard deviation and variance. Correlation analysis revealed that Population Driver Licence (%) had the strongest positive relationship with Petrol Consumption (r = 0.549), whereas Petrol Tax showed a moderate negative correlation (r = -0.463).

Confidence Interval
The calculated 95% confidence intervals were relatively narrow, indicating that the estimated sample means are reliable and provide a good estimate of the population means.

Hypothesis Testing
The calculated test statistics were smaller than the critical value (1.645). Therefore, the Null Hypothesis (H₀) was accepted and the Alternative Hypothesis (H₁) was rejected, indicating that there was no statistically significant difference between the sample and the assumed population mean.
