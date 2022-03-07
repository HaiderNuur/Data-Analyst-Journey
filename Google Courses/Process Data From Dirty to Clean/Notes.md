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

# Week Two
- Number one Cause of poor-quality data = Human Error
- Dirty Data: Data that is incomplete, incorrect or irrelavant to the problem you're trying to solve
- Clean data: Opposite of dirty data
- Data Engineers: Transform data into a useful format for analysis and give it a reliable infrastructure. They develop, maintain and test databases, data processors and related systems. 
- Data Warehouse Specialists: Develop processes and procedures to effectively store and organize data, They make sure that data is available, secure and backed up to prevent loss.

Types of Dirty Data
- Duplicate data: Any data record that shows more than once. Possible Causes: Manual data entry, batch imports, or data migration. Potential harm to business: Skewed metrics or analyses, inflated or inaccurate counts or predictions, or confusion during data retrieval
- Outdated data: Any data that is old that should be replaced with newer and more accurate information. Causes: People changing roles or companies, or software and systems becoming obsolete. Potential Harm: Inaccurate insights, decision-making and analytics
- Incomplete data: Any data that is missing important fields. Causes: Improper data collection or incorrect data entry. Potential harm: Decreased productivity, inaccurate insights, or inability to complete essential services. 
- Incorrect data: Any data that is complete but inaccurate. Causes: Human error inserted during data input, fake information, or mock data. Potential Harm: inaccurate insights or decision-making based on bad information resulting in revenue loss. 
- Inconsistent data: Any data that uses different formats to represent the same thing. Causes: Data stored incorrectly or errors inserted during data transfer. Harms: Contradictory data points leading to confusion or inability to classify or segment customers. 

Data Integrity principles
- Completeness: The degree to which all required measures are known
- Accuracy: The degree of conformity of a measure to a standard or a true value
- Consistency: The degree to which a set of measures is equivalent across systems
- Validity: The concept of using data integrity principles to ensure measures to defined business rules or constraints. 

### Data cleaning tools and techniques
- Removing unwanted data: (good idea to keep a copy of the dataset before doing it)
- Removing duplicates: 
- Removing irrelavant data: 
- Removing extra spaces
- Fixing misspellings
- Inconsistent capitalization
- Incorrect punctuation and other typos
- Removing formatting


*Data merging video is important*
Questions to ask here
- Do I have all the data I need?
- Does the data I need exist within these Datasets?
- Does the data need to be cleaned, or are they ready for me to use?
- Are the datasets cleaned to the same standard?

###### Common data-cleaning Pitfalls
- Not-checking for spelling errors: Misspellings can be as simple as typing or input errors. Most of the time the wrong spelling or common grammatical errors can be detected, but it gets harder with things like names or addresses. For example, if you are working with a spreadsheet table of customer data, you might come across a customer named “John” whose name has been input incorrectly as “Jon” in some places. The spreadsheet’s spellcheck probably won’t flag this, so if you don’t double-check for spelling errors and catch this, your analysis will have mistakes in it. 
- Forgetting to document errors: Documenting your errors can be a big time saver, as it helps you avoid those errors in the future by showing you how you resolved them. For example, you might find an error in a formula in your spreadsheet. You discover that some of the dates in one of your columns haven’t been formatted correctly. If you make a note of this fix, you can reference it the next time your formula is broken, and get a head start on troubleshooting. Documenting your errors also helps you keep track of changes in your work, so that you can backtrack if a fix didn’t work. 
- Not-checking for misfielded values: A misfielded value happens when the values are entered into the wrong field. These values might still be formatted correctly, which makes them harder to catch if you aren’t careful. For example, you might have a dataset with columns for cities and countries. These are the same type of data, so they are easy to mix up. But if you were trying to find all of the instances of Spain in the country column, and Spain had mistakenly been entered into the city column, you would miss key data points. Making sure your data has been entered correctly is key to accurate, complete analysis. 
- Overlooking missing values: Missing values in your dataset can create errors and give you inaccurate conclusions. For example, if you were trying to get the total number of sales from the last three months, but a week of transactions were missing, your calculations would be inaccurate.  As a best practice, try to keep your data as clean as possible by maintaining completeness and consistency.
- Looking at a subset of data and not the whole picture:  It is important to think about all of the relevant data when you are cleaning. This helps make sure you understand the whole story the data is telling, and that you are paying attention to all possible errors. For example, if you are working with data about bird migration patterns from different sources, but you only clean one source, you might not realize that some of the data is being repeated. This will cause problems in your analysis later on. If you want to avoid common errors like duplicates, each field of your data requires equal attention.
- Losing track of the business objectives: When you are cleaning data, you might make new and interesting discoveries about your dataset-- but you don’t want those discoveries to distract you from the task at hand. For example, if you were working with weather data to find the average number of rainy days in your city, you might notice some interesting patterns about snowfall, too. That is really interesting, but it isn’t related to the question you are trying to answer right now. Being curious is great! But try not to let it distract you from the task at hand.  
- Not fixing the source of the error: Fixing the error itself is important. But if that error is actually part of a bigger problem, you need to find the source of the issue. Otherwise, you will have to keep fixing that same error over and over again. For example, imagine you have a team spreadsheet that tracks everyone’s progress. The table keeps breaking because different people are entering different values. You can keep fixing all of these problems one by one, or you can set up your table to streamline data entry so everyone is on the same page. Addressing the source of the errors in your data will save you a lot of time in the long run. 
- NOt analyzing the system prior to data cleaning: If we want to clean our data and avoid future errors, we need to understand the root cause of your dirty data. Imagine you are an auto mechanic. You would find the cause of the problem before you started fixing the car, right? The same goes for data. First, you figure out where the errors come from. Maybe it is from a data entry error, not setting up a spell check, lack of formats, or from duplicates. Then, once you understand where bad data comes from, you can control it and keep your data clean.
- Not backing up your data prior to data cleansing:  It is always good to be proactive and create your data backup before you start your data clean-up. If your program crashes, or if your changes cause a problem in your dataset, you can always go back to the saved version and restore it. The simple procedure of backing up your data can save you hours of work-- and most importantly, a headache. 
- Not accounting for data cleaning in your deadlines/process: All good things take time, and that includes data cleaning. It is important to keep that in mind when going through your process and looking at your deadlines. When you set aside time for data cleaning, it helps you get a more accurate estimate for ETAs for stakeholders, and can help you know when to request an adjusted ETA. 

Additional resources
Refer to these "top ten" lists for data cleaning in Microsoft Excel and Google Sheets to help you avoid the most common mistakes:

### Top ten ways to clean your data: Review an orderly guide to data cleaning in Microsoft Excel: https://support.microsoft.com/en-us/office/top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19

### 10 Google Workspace tips to clean up data: Learn best practices for data cleaning in Google Sheets: https://support.google.com/a/users/answer/9604139?hl=en#zippy=

## Cleaning Data in Spreadsheets
- Conditional formatting is a spreadsheet tool that changes how cells appear when values meet specific conditions.
- Hands on videos on: Conditional formatting, fixing missing values, formats, uses of left, right, trim, concat, countif and so on
- *Workflow automation* : https://www.coursera.org/learn/process-data/supplement/QRQsR/workflow-automation
- *Very Important Different Data Perspective, VLOOKUP and Plotting* https://www.coursera.org/learn/process-data/lecture/BcY0L/different-data-perspectives
- Data mapping: is the process of matching fields from one data source to another
- Schema: a way of describing how something is organized
- Even more data-cleaning techniques: https://www.coursera.org/learn/process-data/lecture/Ei2IH/even-more-data-cleaning-techniques

# Week three
### hands on activity on Cleaning up data with SQL is very important = https://www.coursera.org/learn/process-data/quiz/kU8TQ/hands-on-activity-clean-data-using-sql
SQL learn topics
- Getting data from a table using SELECT statements.
- De-duplicating data using commands like DISTINCT and COUNT + WHERE.
- Manipulating string data with TRIM() and SUBSTR.
- Creating/dropping tables with CREATE TABLE and DROP TABLE.
- Changing data types with CAST.


