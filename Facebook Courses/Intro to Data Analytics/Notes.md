# Week One
- Smart Goal Framework: Specific, Measurable, Achievable, Relevant and time-bound

###### Common Marketing Analytics Objectives:
- Find audiences most likely to convert
- forecast sales based on marketing investment
- evaluate effect of advertising
- determine optimal mix of marketing channels
- identify obstacles in sales funnel


###### KPI: Key Performance Indicators
- Measurable value that can help you track your progress towards your goal. They are measurable, directional and directly related to your goal
- Primary KPI: Directly measures whether you are on track to reach your goal
- Secondary KPI: Correlates to your primary KPI but does not let you confirm your goal is reached

###### OSEMN Framework
- a Data Science process which is useful to breakdown the data analytics projects
- has 5 stages: obtain, scrub, explore, model and interpret.
- Obtain: Gather data from relecvant sources
- Scrub: clean the data to ensure a consistent and useful format
- Explore: Search for patterns
- Model: Generate predictions and insights
- Interpret: better understanding through data

Obtain stage: Gather the data
- Determine what data would be useful
- Evaluate what data are available
- Decide on how the data can be gathered 

Questions to ask
- What data do we need to answer this business question?
- Where do these data live and how do we obtain it?

Questions for evaluating Data Sources
- How recent are the data?
- How were the data collected?
- Are the data sampleed? How?
- How detailed are the data?
- Are there data qquality issues?


- Tabular data types: Spreadsheets, Databases

Scrub: Clean the data to ensure a consistent and useful format
- Remove duplicate records
- Correct inconsistent formatting
- Handle missing values
- Remove inaccurate information
- to ensure an accurate analysis
- to combine datasets together with a consistent format
- Dirty data: Duplicate records, inconsistent formatting, missing values, inaccurate information

Explore: Find significant patterns and trends using statistical trends
- Three steps to exploreing data: Examine variable distributions (by generating statistics and creating visualizations of your features),  examine variable relationships (to discover how different variables relate to one another), and perform statistical tests (to justify weather observations in the variables originated from random chance)
- Feature Engineering: transforming data into a format that is more useful and/or easier to interpret. 

Model
- This phase is about using our data to make predictions with mathematical models.
- Model: A mathematical tool that uses data to observe, understand, and/or make predictions.
- Marketers use models to: project sales, predict likelihood to buy, split audiences into subgroups, find new potential customers etc.
- Two purpose - to predict and to interpret

Interpret
- connect analytic findings back to the business context
- Goals: understand the results of your model, explain your findings and provide actionable insights

Questions to ask at this stage
- what was the objective for your analysis?
- how do the data answer these questions?
- what have you learned from the data?
- how can you apply this to a business context?
- what are the most compelling ways to present the data?
- what is the overall story you want to tell?


# Week Two
week 2 was all about python basics.

# Week three
first parts were about SQL basics

### 3rd part: Pandas
Some useful code snippets:
- df = pd.read_csv('customers.csv')
- df
- df.head()
- df.tail()
- df.head(23)
- df.to_csv('output.csv')
- new_df = pd.read_csv('output.csv')
- new_df.head()
- new_df = pd.read_csv('output.csv', index_col=0)
- df.to_csv('new_output.csv', index = False)
- pd.read_csv('new_output.csv')
- df.shape (returns the no of rows and columns)
- df.columns (returns a list of the Dataframe's columns)
- df.info (returns information regarding all of the columns, including the no of missing (null))
- df.describe() returns statistics about each of the columns
- df["ColumnName"] select a column or columns

Filtering:
- mask_uses_credit_card = df['PaymentMethod'] == 'Credit Card'
- mask_uses_credit_card
- df[df['PaymentMethod'] == 'Credit Card']
- mask_has_card = df['PaymentMethod'].str.contains('Card')
- df[mask_has_card]
- mask_payment_starts_with_c = df['PaymentMethod'].str.startswith('C')
- mask_payment_starts_with_c
- df[mask_payment_starts_with_c]
- mask_dsl = df['InternetService'] == 'DSL'
- mask_year_or_more = df['Tenure'] >= 12
- df[mask_dsl & mask_year_or_more]
- mask_uses_checks = df['PaymentMethod'] == 'Check'
- df[mask_dsl | mask_uses_checks]


- duplicated() : finds duplicate records in a df
- df.duplicated()
- ~ df.duplicated() [swap the results of each record, true making false]
- mask = ~ df.duplicated()
- df[mask] 
- df_dedup = df[mask]
- df_dedup.head
- mask = ~ df_dedup.duplicated(subset=['user_id', 'purchase_id'])
- df_clean = df_dedup[mask]
- df_clean

* df.duplicated(keep='last')
* df.duplicated(keep=false)


- drop the duplicated records and assign the output DataFrame to a new variable called df_cleaned.
> df_cleaned = df[~ df.duplicated()]

- Fix the inconsistencies in the column cust_state [unique column]
> df_cleaned['cust_state'].unique()

- validate the prices in prod_price. remove any rows that are obviously wrong.
# check the max and min and mean
df_cleaned.prod_price.min()
df_cleaned.prod_price.max()
# then set the range upto 1000
df_num_fixed = df_cleaned[~(df_cleaned['prod_price'] >= 1000) 

- how many missing values are there?
> num_nans = df_cleaned.isnull().sum()

- drop any columns with missing values
df_cleaned.dropna(axis = 1)


- df.groupby('subscriptionTier')['totalCost'].mean()
- df.groupby('subscriptionTier')['totalCost'].agg(['mean', 'min', 'max', 'count'])
- df.groupby('subscriptionTier')[['totalCost', 'price']].agg(['mean', 'min', 'max', 'count'])


- value_counts() : returns the count of unique values for a column
- df['subscriptionTier'].value_counts()
- df['subscriptionTier'].value_counts(normalize=True)
- df['monthlyBasePrice'].quantile(0.75) **
- df['monthlyBasePrice'].quantile(1) (or max)
- df['monthlyBasePrice'].quantile(0) (or min) 

# Week Four
Data Visualization considerations:
- choose the right type of chart, graph or diagram
- focus on what's relevant
- color choices: can have significant impact. 

Color-related pitfalls:
- using too much color
- using familiar colors in unexpected ways
- using distinct colors that are hard to distinguish
- not making your visualizations accessible (colorblindness consideration)
