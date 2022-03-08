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
- 



