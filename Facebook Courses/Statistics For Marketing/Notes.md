# Week One
### Measures of Central Tendency
- Descriptive statistics, such as measures of central tendency, give you basic information about the data that you or your company have gathered, so you can better understand your audience, your sales, and your marketing efforts
- 3 ways of measures of central tendency: Mean, Median, Mode
- Mean: Average of data, mean is best when your data is recorded regularly like every day, week or month
- Median: The number in the middle of a sorted data set, median is best when the two groups you're comparing are unbalanced, like one has frequent purchases while one has sporadic purchases or you have numbers in the group that are unusually high or low. 
- Mode: most common number, useful when you are looking at frequencies of categories like which products sold the most or which type of services customers signed up for the most.

### Measures of Dispersion
- Dispersion is how spread out your data points are from one another. this can help you as a marketer understand variance in customer purchases, time spent on your website and customer behavior in general
- Variance: describes the spread of data from the mean,  
- Variance uses: Risk Analysis (if it is too high, you can't accurately predict an outcome and it'll become much higher risk, can also check Data Reliability and Range Targeting (reaching audience)
- Variance can help you understand your risk and better target your audience
- Range: How far your data is spread. Max - Min = Range
- Standard deviation: A measurement of variance that breaks your data set into standardized blocks. it can help you measure variants and help you better understand your customers and your business as a tool
- Outlier: A number so removed from the norm it disrupts the data; data beyond 3 standard deviations from the mean
- Data points clustered tightly around the mean result in smaller standard deviation and lower variance vice versa.
-  Z-scores can help you judge a specific value in your dataset, better target your marketing efforts. it describes the relationship between a specific value and the mean of a data set with standard deviations. Specifically, it explains how many standard deviations of a value is from the mean.
-  Knowing where a specific value falls on a spectrum can be very useful, because it allows you to judge it within context and identify if it is unusually high or low.
-  standard deviation calc formula =STDEV(A1:A23 cell range)
-  Z-score formula: =(Value-Mean)/Standard Deviation

### Frequency tables
- A frequency table is a way to visualize the number of times each value in a set is recorded. use countif function to create.
- A Contingency table is a frequency table with multiple categorical variables at the same time. use countifs 
- Scatter plot: a scatter plot is a simple visualization that compares two variables that are numbers one on the x axis and one on the y axis. 
- Correlation: measure of how related two variables are.
- Correlation coefficient: a number that measures how related two variables are. formula: =CORREL(A:A, B:B)

# Week Two
### Sampling
- Sample: Carefully selected subset of a a population meant to represent the group as a whole.

Central limit theorem:
1. Large samples should have the same mean and standard deviation as the population
2. Large samples normalize data

Types of Sampling Methods
- Probability Sampling: randomized sample selection methods
- Non-probability Sampling: sample selection methods without randomization; inaccurate.

Types of Probability Sampling
- Simple Random Sampling: Everyone in a population has an equal chance of being selected; most random sampling method; used for small populations.
- Systematic Sampling: used when you receive data in a series; select individuals for a sample at a regular interval
- Stratified Sampling: makes sure the proportions of the sample are the same as the population; used when it is important to collect data on smaller groups as well as larger ones within a population
- Cluster Sampling: used when the population is divided into equal subgroups; just need to break your population down into groups and choose a few groups at random.

### Distributions
- Distributions helps to better understand customer demographics and how to market them
- A distribution is created from recorded data and used for the purpose of showing the probability of any possible outcome occuring within your data-set.
- If you have a high variance, you will have short distribution
- if you have a small variance, you will have a tall narrow distribution


Common distributions
- Normal or Gaussian distribution: shaped like a bell. Mean, Median and Mode are the same here. 
- Uniform or rectangular distribution: happens when all elements have an equal chance of happening. 
- Posson Distribution: it will tell you the probability of something happening based on the number of times that something else has happened. 
- Exponential distribution: shape is a sharp curve. 

Data Shape influences
1. Skew: is when the distribution is leaning one way or the other. Positive skew: long tail on positive side, majority of the data will be on the left. For negative skew: scenario is opposite
2. Kurtosis: is the data being pulled up or down. Positive kurtosis pulls the distribution up into a tall, narrow shape. Negative one flattens the curve out into a low, wide shape.  
3. Transformations: are ways in which you can try to normalize your data or remove  a skew. they can't fix kurtosis at all (look for outliers in such cases). 


There are four common transformations you can try when you have an obvious skew that needs to be corrected for. They are:

- Logarithmic Transformation:  To find the logarithmic transformation for a numeric dataset, apply this formula to every value n in the set: =LOG10(n). You can then create a histogram for all these logarithmic values.
- Cube Root Transformation: The formula for the cube root, in Excel and Google Sheets, is =n^(1/3). To find the cube root transformation, apply this cube root formula to every value n in your dataset and create a histogram for all these cube root values.
- Square Root Transformation: Likewise, the formula for the square root is =SQRT(n). To find the square root transformation, apply the square root formula to every value n in your dataset and create a histogram for all these square root values.
- Square Transformation: Finally, the formula for the square of a number is =n^2. To find the square transformation, apply the squaring formula to every value n in your dataset and create a histogram for all these squared values.

### Variables
- variables: a measurement or description of an object, person or place. 
- Quantitative variables: sales, costs, revenue, clicks, conversion rate, bounce rate
- Quantitative variables are of two types: continuous and discrete.
- continuous var: value is obtained by measuring or calculating, can be whole numbers. Ex: customer lifetime value, conversion rate
- discrete var: value is obtained by counting, ex: no of sales, clicks, subscribers.
- Independant var: a variable that is controlled or changed in a test
- Dependent var: a variable that is measured or counted in a test
- 
