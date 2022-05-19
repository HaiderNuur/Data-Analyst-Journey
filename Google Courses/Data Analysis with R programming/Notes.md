# Week One
- The term R is used to refer to both the programming language and the software that interprets the scripts written using it.

- RStudio is currently a very popular way to not only write your R scripts but also to interact with the R software. To function correctly, RStudio needs R and therefore both need to be installed on your computer.

**Benefits of RStudio** 
- RStudio is designed to make it easy to write scripts.
- RStudio makes it convenient to view and interact with the objects stored in your environment.
- RStudio makes it easy to set your working directory and access files on your computer.
- RStudio makes graphics much more accessible for a casual user


***very important: https://www.coursera.org/learn/data-analysis-r/supplement/Q1J3x/when-to-use-rstudio
** https://www.coursera.org/learn/data-analysis-r/supplement/XgjMC/connecting-with-other-analysts-in-the-r-community

# Week Two
- **Very important: Working with dates: https://www.coursera.org/learn/data-analysis-r/supplement/g0l4l/dates-and-times-in-r**
- https://www.coursera.org/learn/data-analysis-r/supplement/xEM9d/other-common-data-structures
- CRAN: Comprehensive R Archive Network- An online archive with R packages, source code, manuals and documentation. 
- Packages are units of reproducible R code that you can use to add more functionality to R
- Packages can be found in repositories, which are collections of useful packages that are ready to install. You can find repositories on Bioconductor, R-Forge, rOpenSci, or GitHub, but the most commonly used repository is the Comprehensive R Archive Network or CRAN. CRAN stores code and documentation so that you can install packages into your own RStudio space. 
- Tidyverse: A system of packages in R with a common design philosophy for data manipulation, exploration, and visualization.
- 8 core tidyverse packages: ggplot2, 
, tidyr, readr, purrr, dplyr, stringr, forcat
- **https://www.coursera.org/learn/data-analysis-r/lecture/MbsrZ/welcome-to-the-tidyverse**
- A vignette is documentation that acts as a guide to an R package. A vignette shares details about the problem that the package is designed to solve and how the included functions can help you solve it. The browseVignettes function allows you to read through vignettes of a loaded package.
- Tidyverse was designed to improve the overall workflow for analysts. Since the packages are all integrated with each other, your analysis will be more efficient. You can use the browseVignettes function to find out more about each package and how to use it.
- https://www.coursera.org/learn/data-analysis-r/supplement/aFF6V/r-resources-for-more-help 
- ggplot2(): Create a variety of data viz by applying different visual properties to the data variables in R
tidyr(): A package used for data cleaning to make tidy data
readr(): importing data (csv to R)
tibbile(): works with data frames
purrr(): works with vectors
string(): strings
forcats(): factors
Factors: store categorical data in R where the data values are limited and usuall based on a finite group like country or year

- A pipe is a tool in R that helps make your code more efficient and easier to read and understand.
- Pipe(R): a tool in R for expressing a sequence of multiple operations, represented with "%>%"


# Week Three
- Data frames: collection of columns, columns should be named, data stored can be many different types, like numeric, factor, or character.
- Tibbles: are like streamlined data frames, never change the data types of the inputs, never change the names of your variables, never create row names, make printing easier.
- Tidy data(R): a way of standardizing the organization of data within R.
- Tidy data standards: variables are organized into columns, observations are organized into rows, each value must have its own cell.
-  Tibbles are like streamlined data frames that are automatically set to pull up only the first 10 rows of a dataset, and only as many columns as can fit on the screen.
- **Very important: https://www.coursera.org/learn/data-analysis-r/supplement/lehtV/file-naming-conventions** 
- **https://www.coursera.org/learn/data-analysis-r/supplement/n5cto/more-on-r-operators**
- Clean: Cleaning functions help you preview and rename data so that it's easier to work with.
Examples: skim_without_chart(), select(), rename_with(), glimpse(), clean_names(), rename()
Organize: Organizational functions help you sort, filter, and summarize your data. 
Examples: mean(), arrange(), summarise(), max(), group_by(), filter(), drop_na(), 
Transform: Transformational functions help you separate and combine data, as well as create new variables.
Examples: separate(), mutate(), unite() 

- Anscombe's quartet: Four datasets that have nearly identical summary statistics. 
- The bias() finds the average amount that the actual outcome is greater than the predicted outcome; it's included in the SimDesign package. If the model is unbiased, the output should be pretty close to 0. 
- https://www.coursera.org/learn/data-analysis-r/lecture/z1TG8/the-bias-function
- https://www.coursera.org/learn/data-analysis-r/lecture/Rf92j/same-data-different-outcome
