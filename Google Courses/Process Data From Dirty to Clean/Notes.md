# Week 1
### Data integrity and analytics
- Data integrity: the accuracy, completeness, consistency and trustworthiness of data
- Data manipulation: the process of changing data to make it more organised and easier to read 
- Clean data + alignment to business objectives = accurate conclusions
- Data (integrity) can be compromised when: replicated, transferred, or manipulated 
- Other ways it can be compromised: human error, viruses, malware, hacking and system failure
### Dealing with insufficient data
- Types of Insufficient data: data from only one source, data that keeps updating, outdated data, geographically-limited data
- Ways to address insufficient data: identify trends with the available data, wait for more data if time allows, talk with stakeholders and adjust your objective. 
- Margin of Error: Since a sample is used to represent a population, the sample’s results are expected to differ from what the result would have been if you had surveyed the entire population. This difference is called the margin of error. The smaller the margin of error, the closer the results of the sample are to what the result would have been if you had surveyed the entire population. 
- Confidence level: How confident you are in the survey results. For example, a 95% confidence level means that if you were to run the same survey 100 times, you would get similar results 95 of those 100 times. Confidence level is targeted before you start your study because it will affect how big your margin of error is at the end of your study. 
- Confidence interval: The range of possible values that the population’s result would be at the confidence level of the study. This range is the sample result +/- the margin of error.

Things to remember when determining the size of your sample
- Don’t use a sample size less than 30. It has been statistically proven that 30 is the smallest sample size where an average result of a sample starts to represent the average result of a population.
- The confidence level most commonly used is 95%, but 90% can work in some cases. 
- Increase the sample size to meet specific needs of your project:
- For a higher confidence level, use a larger sample size
- To decrease the margin of error, use a larger sample size
- For greater statistical significance, use a larger sample size
- *https://www.coursera.org/learn/process-data/supplement/blyd3/calculating-sample-size is very useful on how to calculate sample size*

### Testing your data
- Statistical Power: the probability of getting meaningful results from a test
- Hypothesis testing: A way to see if a survey or experiment has meaningful results
- If a test is statistically significant, it means the results of the test are real and not an error caused by random chance. Usually you need a statistical power of at least 0.8 or 80% to consider your results statistically significant.
- *What to do when there's no data* link: https://www.coursera.org/learn/process-data/supplement/dOyv7/what-to-do-when-there-is-no-data
- Determine the best sample size (given population, confidence level, moe), go to sample size calculator: https://docs.google.com/spreadsheets/d/1UTEMR2ViV7nKEMI_sWQuH2DuQVIuLIHAJlmrg44dooI/edit?usp=sharing
###### Sample size calculator: https://www.coursera.org/learn/process-data/supplement/ZqcDw/sample-size-calculator

### Consider the margin of error
- Margin of error: the maximum amount that the sample results are expected to differ from those of the actual population. 
- To calculate MOE, we need: population size, sample size, confidence level
- MOE calculator: https://docs.google.com/spreadsheets/d/13vbhTBwNV1yqHZ1KOeZOXwqNtR2XNA1NsCrZ9k5iMOA/edit?usp=sharing&resourcekey=0-_5kSt5G6nmVQLwwfiq1XWQ
- Let's think about an example of margin of error. It would be great to survey or test an entire population, but it's usually impossible or impractical to do this. So instead, we take a sample of the larger population. Based on the sample size, the resulting margin of error will tell us how different the results might be compared to the results if we had surveyed the entire population.
Margin of error helps you understand how reliable the data from your hypothesis testing is.
The closer to zero the margin of error, the closer your results from your sample would match results from the overall population.

For example, let's say you completed a nationwide survey using a sample of the population. You asked people who work five-day workweeks whether they like the idea of a four-day workweek. So your survey tells you that 60% prefer a four-day workweek. The margin of error was 10%, which tells us that between 50 and 70% like the idea. So if we were to survey all five-day workers nationwide, between 50 and 70% would agree with our results.

Keep in mind that our range is between 50 and 70%. That's because the margin of error is counted in both directions from the survey results of 60%. If you set up a 95% confidence level for your survey, there'll be a 95% chance that the entire population's responses will fall between 50 and 70% saying, yes, they want a four-day workweek.
Since your margin of error overlaps with that 50% mark, you can't say for sure that the public likes the idea of a four-day workweek. In that case, you'd have to say your survey was inconclusive.

Now, if you wanted a lower margin of error, say 5%, with a range between 55 and 65%, you could increase the sample size. But if you've already been given the sample size, you can calculate the margin of error yourself.

Then you can decide yourself how much of a chance your results have of being statistically significant based on your margin of error. In general, the more people you include in your survey, the more likely your sample is representative of the entire population.
Play video starting at :3:34 and follow transcript3:34
Decreasing the confidence level would also have the same effect, but that would also make it less likely that your survey is accurate.

-  A/B testing (or split testing) tests two variations of the same web page to determine which page is more successful in attracting user traffic and generating revenue. User traffic that gets monetized is known as the conversion rate. A/B testing allows marketers to test emails, ads, and landing pages to find the data behind what is working and what isn’t working. Marketers use the confidence interval (determined by the conversion rate and the margin of error) to understand the results. 
-  All about Margin of Error: https://www.coursera.org/learn/process-data/supplement/INdVZ/all-about-margin-of-error
-  
