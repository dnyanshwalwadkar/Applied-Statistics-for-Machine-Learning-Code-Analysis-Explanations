# Complete-Statistics-with-Real-Life-Dataset

![alt text](https://github.com/dnyanshwalwadkar/Applied-Statistics-for-Machine-Learning-Code-Analysis-Explanations/blob/main/Cover.png)

## Why Statistics for Machine Leraning?
From exploratory data analysis to designing hypothesis testing experiments, statistics play an integral role in solving problems across all major industries and domains.
Statistics helps answer questions like...
1. What features are the most important?
2. How should we design the experiment to develop our product strategy?
3. What performance metrics should we measure?
4. What is the most common and expected outcome?
5. How do we differentiate between noise and valid data?

![alt text](https://github.com/dnyanshwalwadkar/Complete-Statistics-with-Real-Life-Dataset/blob/main/Statistics.png)

## Descriptive Statistics
Descriptive Statistics - offers methods to summarise data by transforming raw observations into meaningful information that is easy to interpret and share in the form of numbers graph, bar plots, histogram, pie chart, etc. Descriptive statistics is simply a process to describe our existing data.

### Measure of Central Tendancy
1. Mean
* The “Mean” is the average of the data.
* Average can be identified by summing up all the numbers and then dividing them by the number of observation.
Mean = X1 + X2 + X3 +… + Xn / n

![alt text](https://github.com/dnyanshwalwadkar/Complete-Statistics-with-Real-Life-Dataset/blob/main/mean.png)

2. Geometric Mean
* The Geometric Mean (GM) is the average value or mean which signifies the central tendency of the set of numbers by finding the product of their values.
* Basically, we multiply the 'n' values altogether and take out the nth root of the numbers, where n is the total number of values.

For example: for a given set of two numbers such as 8 and 1, the geometric mean is equal to √(8×1) = √8 = 2√2.
Thus, the geometric mean is also defined as the nth root of the product of n numbers.
In mathematics and statistics, measures of central tendencies describe the summary of whole data set values.

3. Harmonic Mean
* The Harmonic Mean (HM) is defined as the reciprocal of the average of the reciprocals of the data values.
* It is based on all the observations, and it is rigidly defined.
* Harmonic mean gives less weightage to the large values and large weightage to the small values to balance the values correctly
In general, the harmonic mean is used when there is a necessity to give greater weight to the smaller items.
* It is applied in the case of times and average rates.

4.  Mode
* Mode is frequently occurring data or elements.
* If an element occurs the highest number of times, it is the mode of that data.
* If no number in the data is repeated, then there is no mode for that data.
* There can be more than one mode in a dataset if two values have the same frequency and also the highest frequency.

5. Median
* Median is the 50%th percentile of the data. It is exactly the center point of the data.
* Median represents the middle value for any group. It is the point at which half the data is more and half the data is less. - - Median helps to represent a large number of data points with a single data point

## Measure of Variability/Dispersion
1. Variance
* In statistics, the variance is a measure of how far individual (numeric) values in a dataset are from the mean or average value.
* The variance is often used to quantify spread or dispersion. Spread is a characteristic of a sample or population that describes how much variability there is in it.
* A high variance tells us that the values in our dataset are far from their mean. So, our data will have high levels of variability.
* On the other hand, a low variance tells us that the values are quite close to the mean. In this case, the data will have low levels of variability.

2. Standard Deviation
* Standard deviation is a measure of dispersement in statistics.
* “Dispersement” tells you how much your data is spread out.
* Specifically, it shows you how much your data is spread out around the mean or average

##  Shape of Data
1. Symmetric
In the symmetric shape of the graph, the data is distributed the same on both sides.
In symmetric data, the mean and median are located close together.
The curve formed by this symmetric graph is called a normal curve.
2. Skewness
Skewness is the measure of the asymmetry of the distribution of data.
The data is not symmetrical (i.e) it is skewed towards one side.
--> Skewness is classified into two types.

![alt text](https://github.com/dnyanshwalwadkar/Complete-Statistics-with-Real-Life-Dataset/blob/main/shapeofData.png)

### Positive Skew
### Negative Skew
1. Positively skewed:

In a Positively skewed distribution, the data values are clustered around the left side of the distribution and the right side is longer.
The mean and median will be greater than the mode in the positive skew.

2. Negatively skewed

In a Negatively skewed distribution, the data values are clustered around the right side of the distribution and the left side is longer.
The mean and median will be less than the mode.

3. Kurtosis
Kurtosis is the measure of describing the distribution of data.
This data is distributed in different ways. They are:
* Platykurtic
* Mesokurtic
* Leptokurtic
 Platykurtic: The platykurtic shows a distribution with flat tails. Here the data is distributed faltly . The flat tails indicated the small outliers in the distribution.

Mesokurtic: In Mesokurtic, the data is widely distributed. It is normally distributed and it also matches normal distribution.

Leptokurtic: In leptokurtic, the data is very closely distributed. The height of the peak is greater than width of the peak.

![alt text](https://github.com/dnyanshwalwadkar/Applied-Statistics-for-Machine-Learning-Code-Analysis-Explanations/blob/main/kurtosis.jpg)

# Inter Quartile Range(IQR)
The interquartile range tells you the spread of the middle half of your distribution.
Quartiles segment any distribution that’s ordered from low to high into four equal parts. The interquartile range (IQR) contains the second and third quartiles, or the middle half of your data set.
 
## Range 
The range of data is the difference between the maximum and minimum element in the dataset.

## Mean Absolute Deviation(MAD)
The mean absolute deviation of a dataset is the average distance between each data point and the mean. It gives us an idea about the variability in a dataset.
Mean absolute deviation helps us get a sense of how "spread out" the values in a data set are.


![alt text](https://github.com/dnyanshwalwadkar/Applied-Statistics-for-Machine-Learning-Code-Analysis-Explanations/blob/main/boxplot.png)


# Inferential Statistics


Inferential Statistics - offers methods to study experiments done on small samples of data and chalk out the inferences to the entire population (entire domain).
1.  Population Vs Samples:
In statistics, the population is a set of all elements or items that you’re interested in. Populations are often vast, which makes them inappropriate for collecting and analyzing data. That’s why statisticians usually try to make some conclusions about a population by choosing and examining a representative subset of that population.

This subset of a population is called a sample. Ideally, the sample should preserve the essential statistical features of the population to a satisfactory extent. That way, you’ll be able to use the sample to glean conclusions about the population.

![alt text](https://github.com/dnyanshwalwadkar/Applied-Statistics-for-Machine-Learning-Code-Analysis-Explanations/blob/main/Infernce.png)

2. Data Sampling:
Data sampling is a statistical analysis technique used to select, manipulate and analyze a representative subset of data points to identify patterns and trends in the larger data set being examined.

* Different types of sampling technique:
Probability Sampling: In probability sampling, every element of the population has an equal chance of being selected. Probability sampling gives us the best chance to create a sample that is truly representative of the population
* Non-Probability Sampling: In non-probability sampling, all elements do not have an equal chance of being selected. Consequently, there is a significant risk of ending up with a non-representative sample which does not produce generalizable results

![alt text](https://github.com/dnyanshwalwadkar/Applied-Statistics-for-Machine-Learning-Code-Analysis-Explanations/blob/main/Infernece2.png)

# Central Limit Theorem:
The Central Limit Theorem states that the sampling distribution of the sample means approaches a normal distribution as the sample size gets larger.
The sample means will converge to a normal distribution regardless of the shape of the population. That is, the population can be positively or negatively skewed, normal or non-normal.

CLT states that — as the sample size tends to infinity, the shape of the distribution resembles a bell shape (normal distribution). The center of this distribution of the sample means becomes very close to the population mean — which is essentially the law of large numbers.
So, how is the Central Limit Theorem used?

It enables us to test the hypothesis of whether our sample represents a population distinct from the known population. We can take a mean from a sample and compare it with the sampling distribution to estimate the probability whether the sample comes from the known population.

# Confiedence Interval:
Confidence Interval is a type of estimate computed from the statistics of the observed data which gives a range of values that’s likely to contain a population parameter with a particular level of confidence.
A confidence interval for the mean is a range of values between which the population mean possibly lies.
