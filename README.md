# Feature-engineering-outlier-removal-using-IQR-method-for-skewed-feature
I applied the IQR method to identify outliers by calculating the range between the 25th and 75th percentiles of each feature's distribution. Data points lying outside a specified range, typically defined as 1.5 times the IQR (interquartile range) beyond the quartiles, were flagged as outliers and subsequently removed. This method is particularly effective for features with non-normal distributions where the mean and standard deviation may not accurately reflect the data's central tendency and variability. By removing outliers using the IQR method, I aimed to enhance the robustness of statistical analyses and machine learning models, ensuring that extreme values did not unduly influence model training or subsequent analytical insights.
