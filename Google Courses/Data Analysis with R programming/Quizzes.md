# Week 1
## Weekly Challenge
- A data analyst uses words and symbols to give instructions to a computer. What are the words and symbols known as? 
> Programming Language
- What are the benefits of using a programming language for data analysis? Select all that apply.
> Easily reproduce and share the analysis, Clarify the steps of the analysis, save time
- Which of the following are benefits of open-source code? Select all that apply. 
> Anyone can fix bugs in the code, Anyone can use the code for free, Anyone can create an add-on package for the code
- Which of the following are benefits of using R for data analysis? Select all that apply. 
> Process lots of data, Reproduce and share an analysis, Create high-quality data visualizations 
- A data analyst needs to quickly create a series of scatterplots to visualize a very large dataset. What should they use for the analysis? 
> R programming langua> mdy()

- What is a type of application that brings together all the tools a data analyst may want to use in a single place? 
> Integrated development environment (not dashboard)
- Fill in the blank: When you execute code in the source editor, the code automatically also appears in the _____.
> R console 
- In RStudio, where can you find and manage all the data you currently have loaded?
> environment pane
- RStudio’s integrated development environment includes which of the following? Select all that apply.
> An area to manage loaded data, A console for executing commands, An editor for writing code 

# Week Two
- When working in R, for which part of the data analysis process do analysts use the tidyr package?
> Data cleaning
- Which tidyverse package contains a set of functions, such as select(), that help with data manipulation?
> dplyr
- An analyst is organizing a dataset in RStudio using the following code:
arrange(filter(Storage_1, inventory >= 40), count)
Which of the following examples is a nested function in the code?
> filter
## Weekly challenge
- An analyst comes across dates listed as strings in a dataset, for example December 10th, 2020. To convert the strings to a date/time data type, which function should the analyst use?
> mdy()
- A data analyst wants to assign the value 50 to the variable daily_dosage. Which of the following types of operators will they need to write that code? 
> assignment
- Which of the following are included in R packages? Select all that apply.
> Tests for checking your code, Sample datasets, Reusable R functions
- When an analyst installs a package that is not in Base R, where does R call the package from?
> The CRAN archive
# Week Three
### Data frames
- Which of the following are best practices for creating data frames? Select all that apply.
> Columns should be named, each column should contain the same number of data items
- Why are tibbles a useful variation of data frames>
> Tibbles make printing easier
- Tidy data is a way of standardizing the organization of data within R.
> True
- Which R function can be used to make changes to a data frame?
> mutate()
### Cleaning data
- A data analyst is cleaning their data in R. They want to be sure that their column names are unique and consistent to avoid any errors in their analysis. What R function can they use to do this automatically?
> clean_names()
## Weekly Challenge
- A data analyst is considering using tibbles instead of basic data frames. What are some of the limitations of tibbles? Select all that apply.
> Tibbles won’t automatically change the names of variables, Tibbles can never change the input type of the data, won't overload the console.
- A data analyst creates a data frame with data that has more than 50,000 observations in it. When they print their data frame, it slows down their console. To avoid this, they decide to switch to a tibble. Why would a tibble be more useful in this situation? 
> Tibbles won’t overload the console because they automatically only print the first 10 rows of data and as many variables as will fit on the screen
- A data analyst is working with a data frame named cars. The analyst notices that all the column names in the data frame are capitalized. What code chunk lets the analyst change all the column names to lowercase? 
> rename_with(cars, tolower)
- A data analyst is working with the penguins dataset in R. What code chunk will allow them to sort the penguins data by the variable bill_length_mm? 
> arrane(penguins, bill_length_mm)
- A data analyst is working with a data frame named salary_data. They want to create a new column named wages that includes data from the rate column multiplied by 40. What code chunk lets the analyst create the wages column? 
> mutate(salary_data, wages = rate * 40)
- A data analyst is working with a data frame named retail. It has separate columns for dollars (price_dollars) and cents (price_cents). The analyst wants to combine the two columns into a single column named price, with the dollars and cents separated by a decimal point. For example, if the value in the price_dollars column is 10, and the value in the price_cents column is 50, the value in the price column will be 10.50. What code chunk lets the analyst create the price column? 
> unite(retail, "price", price_dollars, cents, sep = ".")
- A data analyst uses the bias() function to compare the actual outcome with the predicted outcome to determine if the model is biased. They get a score of 0.8. What does this mean?
> not biased

