Dataset : bhp.csv and heights.csv

Normal distribution, also known as Gaussian distribution, is a probability distribution that is symmetric around its mean,
meaning that the data near the mean are more frequent in occurrence than the data far from the mean. In a normal distribution:

1)The mean (average) is at the center.
2)The standard deviation determines the spread of the distribution.
3)About 68% of the data falls within one standard deviation of the mean.
4)About 95% of the data falls within two standard deviations.
5)About 99.7% of the data falls within three standard deviations.


Z-score (or standard score) is a statistical measurement that describes a value's relation to the mean of a group of values. 
It is measured in terms of standard deviations from the mean. The formula for calculating the z-score of a data point x, given 
the mean (μ) and the standard deviation (σ), is:


Z= (x-μ)/σ
​
 

A Z-score of 0 indicates that the data point's score is identical to the mean score, a Z-score of 1.0 indicates a value that 
is one standard deviation from the mean, and so on.

The Z-score can be used to identify outliers or to compare scores from different distributions.

In the context of the previous code example:

In Step 3, the data is filtered based on whether the price_per_sqft is within 4 standard deviations of the mean.
In Step 5, the z-scores are calculated for each data point, and data points with absolute z-scores greater than 4 are removed.
Both steps (3 and 5) aim to identify and remove outliers based on a statistical measure (standard deviations or z-scores) from a normal distribution of the data.
