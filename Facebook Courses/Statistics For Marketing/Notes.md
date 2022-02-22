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


# Week Three
###  Experimental design review
- Sometimes data will simply get handed to you, but sometimes you will have to perform a study to gather data that answers specific business questions you have been given.
- Experimental Design is the process of planning out your study and must be done before doing anything else. 

It has 5 basic steps
1. Questioning or Evaluation question: Business or data related questions marketing analysts ask about their data. When formulating the question to be answered by your study, remember to be specific, keep the goal in mind, and know your resources.
2. Hypothesis: A hypothesis is a proposed explanation based on the limited information you have already as a starting point for further investigation. This doesn’t have to be a formal research hypothesis. Three Parts of a Clear Hypothesis: What will change?, How will it change? What will cause the change? For example, we might form a hypothesis that says: “Sales will increase with a higher marketing budget.” In this case, sales are the variable we have identified as “what is going to change.” Our hypothesis also addresses “how sales change” by anticipating that sales will increase. Finally, our hypothesis addresses the question of “what will cause sales to increase?”: a higher marketing budget.
3. Required variable: Determining required variables is the step in the experimental design process where you sit down and figure out exactly what information you will need to answer your question and test your hypothesis. First and foremost, you will need to determine the independent and dependentvariables in your study. The variable whose effect we measure is called a dependent variable. In our color influence test, the independent variable would be the website’s color scheme and the dependent variable would be the number of sales.
4. Choosing a measurement approach: Once you’ve determined what variables you require data for, you next will need to determine how to acquire that data! There are many different types of experimental set-ups, or measurement approaches, you might choose from, but usually you want to keep things as simple as possible. The approach described above, for our study of color influence on sales, is a good example of a simple measurement approach (often called an “A/B Test”) where we just present our independent variable in two options (options A and B) and measure the difference in the dependent variable between those two options. If you are in doubt about what type of measurement approach to use, don’t hesitate to ask another marketing analyst which type of study they think would be most appropriate for acquiring your required variables!
5. Selecting an analysis: Understanding the different types of analyses you might perform with your marketing data, once you’ve gathered it, is a more technical aspect of marketing analytics


![neOB1Db-RnKjgdQ2_iZy6g_ea1c012db3394ede867c844dda306ff1_01---Design-Example](https://user-images.githubusercontent.com/20629270/154934518-c6fcffe8-7062-455d-9f27-50484ae25971.png)


### Hypothesis testing
- Hypothesis testing: you take the data you collected and run an analysis to see if your hypothesis is true. 

2 possible hypothesis for any analysis:
- Null Hypothesis (H0): is default, always says there is no difference. can think of this as a negative result to a test.
- alternative hypothesis (H1): states that there is a difference. positive result
- either of them is true always
- AB testing: you have two versions. For null hypothesis: A = B, no difference. But for alternative, there is a difference.
- P-Value: probability that the difference is random chance. it is the probability that the difference between groups was just chance. For example, if one type of cat food sold more than another type of cat food, the p-value will tell you if the difference in sales is just chance, or if there is a measurable reason behind why one sold more. P-value is written as a decimal, but you can think of it as a percent. P-value of 0.05 is the same as five percent. if your p-value is less than or equal to 0.05, that means there is a significant difference between whatever you are comparing. Saying something is significant in statistics means that an analysis has proven that there is a difference. If you have a p-value of 0.05 or 5 percent, that means there's only a 5 percent chance of being wrong if your hypothesis states that there is a difference between the variables being analyzed. If you accept the alternative hypothesis, then there is a difference and reject the null hypothesis, that there is no difference. You will be correct 95 percent of the time.
- Alpha: Statistical cutoff for p-value. default value: 0.05

- Confidence interval: range in which the true mean of population will fall. % of confidence interval.

Factors that impact data reliability: 
- variance: a large variance indicates that your data is generally less reliable, and vice versa
- confidence intervals: a large confidence interval indicates that your data is less reliable and vice versa
- Sample size: should be large enough to be reliable

- how to calculate confidence interval: 
###### =TINV(Alpha, SampleSize - 1) * (StandardDeviation/SQRT(SampleSize))

most common Statistical analyses for Testing Hypotheses:
- t-test: used when you have two quantitative groups.
- Chi-square: 
- ANOVA(analysis of variance)


Student's t-test: checks for a significant difference between two groups that are continuous variables.
- formula: ttest(Group1, Group2, Tails, Type)
- here Tail = how we distribute the variance. if you're checking how one group is larger than the other, can use one tail test. a two tail test distributes the variance equally to both sides. This checks to see if either group is larger or smaller. 
- two tail test: =ttest(G1, G2, 2, Type)
- Types: Two types: "paired" - means that you're taking both samples from the same population. An example would be if you recorded the number of hits on a website, then change the website, then recorded the number of hits again. It's the same website but your groups would be before the change and after the change. "Independent" - means that the groups are separate. if you've two versions of a website running at the same time to see which was doing better, the groups would be independent.

### Common mistakes in Statistics
- Bias:  Statistical bias is when a model, experiment, or survey is conducted in such a way that the result is unrepresentative of the population, it's the difference between expected and actual values of a population.

Types of Bias: 
- Survey: bias that included actions you take while giving a survey that will skew the results. Types include Order Bias (first question/answer has possible inherent bias), Leading questions (lead the person to an answer), Recall bias (when they forget about past and you ask for that)
- Culture bias: certain words, phrases or references that are particularly for one area
- Confirmation bias: you are actively looking for the answers for which your hypothesis is true
- Observation bias: people act differently when they know they are being watched, may not get the actual answers.
- Selection bias: if you select a sample that no longer represents the population


- 



