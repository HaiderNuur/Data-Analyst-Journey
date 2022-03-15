# Week One: Organize data to begin analysis
### Data analysis basics
- Analysis: The process used to make sense of the data collected
- The goal of analysis is to identify trends and relationships within data so you can accurately answer the question you're asking

The 4 phases of analysis
1. Organise data
2. Format and adjust data: sort and filter data
3. Get input from others
4. Transform data: identifying relationships and patterns between the data and make calculations based on the data you have.


- Sorting involves arranging data into a meaningful order to make ite sier to understand, analyze and visualize.
- Sorting and Filtering: https://www.coursera.org/learn/analyze-data/supplement/6xPhu/sorting-and-filtering-in-sheets-and-excel

# Week Two: Formatting and Adjusting data
**Week 2 is really important**
- FROM one type to another in Spreadsheet using CONVERT funtion is really awesome. Example -  mph to m/s: =CONVERT(A2, "mph","m/s")
- **Converting Data in spreadsheets: https://www.coursera.org/learn/analyze-data/supplement/H7GTe/converting-data-in-spreadsheets**
- Data validation: allows you to control what can and can't be entered in spreadsheet
- Uses:Add dropdown lists with predetermined options, Create custom checkboxes,protect structured data and formulas 
- data validation can help your team track progress, breaking when working in big teams, help you customize tables to your needs
- **Transforming data in SQL: https://www.coursera.org/learn/analyze-data/supplement/HqeNj/transforming-data-in-sql**
- which route users take the most

**SELECT
    usertype,
    concat(start_station_name, " to ", end_station_name) AS Route,
    count(*) as num_trips,
    ROUND(AVG(cast (tripduration as int64)/60), 2) as Duration
FROM `bigquery-public-data.new_york_citibike.citibike_trips` 
GROUP BY 
    start_station_name, end_station_name, usertype
ORDER BY 
    num_trips DESC 
LIMIT 10; 
**

- Working with LEN, LEFT, RIGHT, FIND in spreadsheets
- **Advanced Spreadsheet tips and tricks: https://www.coursera.org/learn/analyze-data/supplement/6Vp5U/advanced-spreadsheet-tips-and-tricks**

# Week Three : aggregate data for analysis
### VLOOKUP for data aggregation
- Benefits of data aggregation: identify trends, make comparisons, gain insights
- subquery: a query within a query
- Vertical Lookup: a function that searches for a certain value in a column to return a corresponding piece of information

Problems faced in VLOOKUP
- doesn't work if data has wrong format and extra space: solve with value and trim first
- only returns first match if there's duplicates (remove duplicates)

Troubleshooting questions
- How should I prioritize these issues?
- In a single sentence, what's the issue I'm facing?
- What resources can help me solve the problem?
- How can i stop this problem from happening in the future?

VLOOKUP issues
- can only return value data from the right, it can't look left. (copying and pasting the columns in the right)
- table array should be always absolute reference.
- if changes data, it doesn't work. can protect the sheet or use Match function
- should always use FALSE, exact match

- **VLOOKUP Core Concepts: https://www.coursera.org/learn/analyze-data/supplement/SNmqP/vlookup-core-concepts**
### USE JOINs to aggregate data in SQL
- 4 Common JOINs: Inner, Left, Right, Outer
- Inner Join: a function that returns records with matching values in both tables, by default JOIN is inner join
- Left Join: a function that will return all the records from the left table and only the matching records from the right table
- Right join: opposite of left join
- Outer join: a function that combines RIGHT and LEFT join to reutrn all matching records in both tables
- Importance of Aliases: https://www.coursera.org/learn/analyze-data/supplement/qURXP/secret-identities-the-importance-of-aliases
- Using JOINs effectively: https://www.coursera.org/learn/analyze-data/supplement/DBOi7/using-joins-effectively
- using Count and count distinct
- count distinct: a query that only returns the distinct values in a specified range


### Using subqueries to aggregate data
- Queries within queries: https://www.coursera.org/learn/analyze-data/lecture/Zkoae/queries-within-queries
- HAVING: allows you to add a filter to your query instead of the underlying table that can only be used with aggregate functions
- CASE: returns records with your conditions by allowing you to include if/then statements in your query
- using Subqueries to aggregate data: https://www.coursera.org/learn/analyze-data/lecture/JjPZ5/using-subqueries-to-aggregate-data
- **SQL functions and subqueries: https://www.coursera.org/learn/analyze-data/supplement/SthVU/sql-functions-and-subqueries-a-functional-friendship**
-
