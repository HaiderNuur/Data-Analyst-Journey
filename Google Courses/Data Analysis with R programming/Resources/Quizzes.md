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
# Week Four
- In ggplot2, you can use the _____ function to specify the data frame to use for your plot. 
> ggplot()
- In ggplot2, you use the plus sign (+) to add a layer to your plot. 
> True
- In ggplot2, what function do you use to map variables in your data to visual features of your plot?
> aes()
- Which of the following functions let you display smaller groups, or subsets, of your data?
> facet_wrap()
- What is the role of the x argument in the following code? ggplot(data = diamonds) +
     geom_bar(mapping = aes(x = cut))
> an aesthetic
- A data analyst creates a scatterplot with a lot of data points. It is difficult for the analyst to distinguish the individual points on the plot because they overlap. What function could the analyst use to make the points easier to find? 
> geom_jitter()
- Which of the following are benefits of adding labels and annotations to your plot? Select all that apply. 
> Helping stakeholders quickly understand your plot, Highlighting important data in your plot, Indicating the main purpose of your plot 
- A data analyst is creating a plot for a presentation to stakeholders. The analyst wants to add a caption to the plot to help communicate important information. What function could the analyst use? 
> labs()
- What function can you use to put a text label inside the grid of your plot to call out specific data points? 
> annotate()
## Weekly Challenge
- Which of the following are operations you can perform in ggplot2? Select all that apply. 
> Change the colors and dimensions of your plot, Create scatterplots and bar charts
- In ggplot2, what symbol do you use to add layers to your plot?
> + sign
- A data analyst uses the aes() function to define the connection between their data and the plots in their visualization. What argument is used to refer to matching up a specific variable in your data set with a specific aesthetic?
> mapping()
- A data analyst creates a scatterplot with a lot of data points. The analyst wants to make some points on the plot more transparent than others. What aesthetic should the analyst use? 
> color
- Fill in the blank: The _____  creates a scatterplot and then adds a small amount of random noise to each point in the plot to make the points easier to find.
> geom_jitter()
- Fill in the blank: Markdown is a _____ for formatting plain text files.
> syntax
- A data analyst creates an interactive version of their R Markdown document to share with other users that allows them to execute code the analyst wrote. What did they create?
> An R Notebook

# Week 5
## Weekly challenge
- R Markdown is a file format for making dynamic documents with R. What are the benefits of creating this kind of document? Select all that apply. 
> Save, organize, and document code, Create a record of your cleaning process, Generate a report with executable code chunks 
- A data analyst finishes editing an R Markdown notebook and wants to convert it to a new format they can share. What are their options? Select all that apply.
> Dashboards, slide presentations, word documents
- A data analyst wants to change their header to be one font size smaller. What should they add to their markdown syntax? 
> Hashtag
- Fill in the blank: _____ code is code that can be inserted directly into a .rmd file. 
> Markdown
- A data analyst wants to add a bulleted list to their R Markdown document. What symbol can they type to create this formatting?
> Asterisk
- Fill in the blank: Code added to an .rmd file is usually referred to as a code _____. This allows users to execute R code from within the .rmd file. 
> chunk
- A data analyst adds specific characters before and after their code chunk to mark where the data item begins and ends in the .rmd file. What are these characters called?
> Delimeters
- A data analyst who works with R creates a weekly sales report by remaking their .rmd file and converting it to a report. What can they do to streamline this process?
> Create a template

