# Week one

##### Practice quiz: Goals and KPIs
- Which of the following is true about having access to data? Choose all that apply.

Answer: It helps to plan and forecast the results of marketing action, It helps marketers evaluate the success of advertising.
- Before obtaining data (the “O” in the OSEMN process), which should be the very first step in the cycle?

Answer: Determine the objective of analysis
- True or false: KPIs are measurable values that can help you track your progress towards your goal. 

Answer: True


##### Practice quiz: The OSEMN Process
- Another popular framework for data analytics projects is the Cross Industry Standard Process for Data Mining (CRISP-DM). It has six stages: Business Understanding, Data Understanding, Data Processing, Modeling, Evaluation and Deployment. The CRISP-DM phase of Evaluation is likely closest to which stage of the OSEMN framework?

Answer: Interpret
- An online bookstore wants to analyze what book titles they should advertise to drive more sales. They’ve already pulled their historic sales and web traffic data as well as book title details. What is the MOST likely best next step based on the OSEMN framework?

Answer: Ensure that the data gathered is generally “clean” & well-formatted and make changes as necessary.
- Looking at some data about user profiles for a website, we notice that a relatively large portion of the users (25%) have their age listed as over 100 years old. Is this dirty data? (Select the most appropriate answer.)

Answer: It’s PROBABLY dirty data but we need to know more about the data before deciding what to do with it.

### Graded Quiz
- Before exploring data and conducting analysis, it is important to _____________ 

Answer: ensure the data are clean by removing any duplicate data and have consistent formatting.
- Which stage of the OSEMN process has the goal of trying to understand the data as a whole and learn the patterns in the data?
Answer: Obtaining
- You've been asked to conduct an analysis on customer interests to identify other product offerings these consumers might be interested in. Using the OSEMN framework what would be a sensible approach? 

Answer: Get the data, ensure it is accurate and well-formatted, conduct statistical analysis, generate predictions and insights, translate results to tell a story.
- An analyst has been working with their clients to define business goals and identified questions to answer. They are now ready to dive into the OSEMN process. Which stage of the OSEMN process would likely be the next step for this analyst?

Answer: Scrubbing
- During the Explore step of the OSEMN framework, you attempt to get familiar with your data. Which of the following is NOT a part of the exploration step?

Answer: Reformat columns to be consistent such as reformatting a column of date values.
- The iNterpret stage of the OSEMN framework is the last stage of the process. What is the primary goal of a data analysis project?

Answer: Generate insights and understanding.
- What does the T in the SMART acronym stand for?
Answer: Timely
- KPIs are measurable values that are suggested targets but don’t usually align with your goals.
Answer: False
- During the Explore step of the OSEMN framework, you attempt to get familiar with your data. Which of the following is NOT a way to examine your variable distributions and relationships?

Answer: Create a statistical model to make predictions about our data



# Week two
### Graded Quiz: Loading and Running a Python Program
- Which of the following data types store tabular data? Choose all that apply. > CSV, XLSX
- Which of the following data types typically have delimited data? Select all that apply. > CSV, TXT
- Logical thinking is a skill that must be practiced like any other. True or False? > true
- It is important to memorize all of the syntax and every function. True or False? > False
- Which of the following describes Python? Check all that apply. > Object-oriented, general purpose, open-source
- Python is only used for data analytics. True or False? > False
- When writing code in a Jupyter notebook, you should write all of your code in one cell. > False
- Sometimes you need a little help while writing code in a Jupyter notebook. You can use a question mark before or after a function and then execute the cell to learn more about the function. > True
- Json files are structured in a nested structure. True or False? > True
- When writing code in a Jupyter notebook, you should separate your code into different cells so there is only one line per cell. > False





# Week Three
### practice quiz: finding and removing duplicate records : (using) Pandas
- Given that you have a Pandas DataFrame `df`, how would you export the DataFrame to the CSV file “my_data.csv”?
> df.to_csv(“my_data.csv”)
- What code would get you just the data for `Column 2`? > df["Column 2"]
- What code would get you how many rows and columns are in a DataFrame `df`? > df.shape

## Graded quiz: Pandas and SQL
Question 1: Say I have the given data loaded as a DataFrame `df` using Pandas. We know that the `customerID` column has a unique value (representing a different customer).
https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/fjsFo2qfTFS7BaNqnzxU1Q_b3dee44de7d74b7ba148bf7de227b1f1_Pandas-and-SQL-Quiz-Table.png?expiry=1643932800000&hmac=ubziw1clhJ9QztsYVCPGqO_qmaBLHRlGK80VN9RDlQE 
What code would I write to find out how many customers there are that have the security add on?

Answer: df.groupby(‘addOn_security’)[‘customerID’].count()

Question 2: 
What code would I write to find out how many customers have the security add on?

Answer: df[‘addOn_security’].value_counts()

Question 3: How would you interpret this output?
df[ 'totalCosts' ].quantile(0.8)
8.99

Answer: 80% of the data has a value of 8.99 or less for the totalCost column

Question 4: What code would you write to get just the single column `industry`?

Answer: df[‘industry’]

Question 5: You can find the list of columns with `df.columns()`

Answer: False

Question 6: What code would you write to get all the rows where `totalCost` is less than $6?

Answer: df[ df[‘totalCost’] < 6.00 ]

Question 7: What code would you write to get all the rows where `industry` starts with the letter “R”?

Answer: df[ df[‘industry’].str.startswith(“R”) ]

Question 8: Which code would you write to filter a DataFrame `df` so that you keep only the first instance of a duplicate?

Answer: df[df.duplicated(keep=False) ]

Question 9: What code would I write to find out how many customers there are in each subscription tier?

Answer: df[‘subscriptionTier’].value_counts()






# Week Four
### Practice Quiz: Chart Types and Basic Tableau Graphs
- Which type of chart is usually best suited for visualizing the relationship of measurements to another ordered series of data, such as time?
> A Line chart
- True or false: The order in which you double-click a data field may affect the chart that Tableau generates?
> True
- True or false: Tableau can only connect to data from an Excel file or CSV file? > False
- On the Tableau start page, which of the following connection types would you select if you want to connect to data in a CSV file?
> Text file
- True or false: If you change the name of a column in Tableau’s data preview pane, this will change the data in your Excel or CSV file.
> False

### Practice Quiz: Building Charts in Tableau II Practice
- Of all the chart-making options we’ve covered, which of these is “easiest” (i.e., requires the least input from you)? > The “double-click” method.
- True or False: you can use the “Show Me” tool even after you’ve created a chart using other methods? > True
- In Tableau, for charts that are drawn on a pair of axes, how do you specify what data you want represented on the vertical axis (or Y-axis)? > By dragging the target data field from the Data Pane to the “Row Shelf.”



- 



