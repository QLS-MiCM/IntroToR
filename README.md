# Introduction to programming in R

## Overview

This workshop is beginner-level introduction to programming in R. The course is designed to be taught in one session of 4 hours and is focused on the application of R to the analysis of tabular data from medical datasets.

## The Workshop Materials

Throughout this course, we will primarily use our dedicated workshop website: 👉 [Introduction to R Workshop: https://martinahyang.github.io/IntroToR/](https://martinahyang.github.io/IntroToR/)

We will use this site to cover the foundational concepts of R, while performing **hands-on exercises** together in the **RStudio**. All necessary code and resources are provided on the site for your convenience.

## Prior knowledge

-   No previous programming experience is required.
-   Please review the following topics if you're not comfortable with them:
    -   basic linear algebra (operations with vectors and metrices)
    -   mathematical operations (exponentials, logarithms)
    -   basic statistics (mean, variance, median, standard deviation)
    -   logical statements (AND, OR, NOT)

## Sofware requirements

-   [R \>4.0](https://www.r-project.org)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/)

**You could refer to the step-by-step instructions [Getting Started: Installing R and RStudio](https://martinahyang.github.io/IntroToR/WebsiteCodes/Setup.html).**

Once you have setup R and RStudio copy the code below to install the packages required for the workshop.

```{r}
install.packages(c("data.table","datasets","devtools","dplyr","ggplot2","plyr","medicaldata","gapminder","RColorBrewer","rmarkdown","stringr","tidyr","tidyverse","viridis"))
```

## Workshop Outline

### 1. R basics

In the first module of the workshop, the goals are to (1) familiarize with the language and the logic behind it; (2) Get started with R studio and create your first project; (3) Configure the working directory with a common standard structure; (4) Create your first `.R` file to write down the live code; (5) Compute arithmetic operations; (6) Use logical operators; (7) Get fluent in R's console; (8) Learn how to ask for help within R ; and (9) get comfortabble with installing packages.

**Module content:**

-   Syntax
-   Aritmetic Operations
-   Creating variables
-   Logical operators
-   Seeking help
-   Installing packages
-   Hands on: basics

### 2. Data types: attributes and built-in functions

In this section participants will (1) understand the differences between classes, objects and data types in R; (2) create objects of different types, learn about their attributes and apply some built-in functions in R; (3) Subset and index objects; and (4) get comfortable with vectorized operations.

**Module content:**

-   Vectors
-   Lists
-   Factors
-   Data frames
-   Arrays
-   Coercion
-   Hands-on: data types

### 3. Basic data manipulation

In this module participants will (1) learn how to read/write data to/from files with different formats (.tsv, .csv); (2) become familiar with basic data-frame operations; (3) index and subset data frames using base R; (4) manipulate individual data frame columns; and (5) learn how to join columns and rows of different data frames using base R.

**Module content:**

-   Reading/writing data
-   Exploring data frames
-   Hands-on: basic data manipulation

### 4. Advanced data manipulation

The fourth module participants will (1) familiarize with the dplyr syntax; (2) create pipes with the operator `%>%`; (3) perform operations on data frames using dplyr and tidyr functions; and (4) implement functions from external packages by reading their documentation in R

**Module content:**

-   Handling data frames with dplyr
-   Other useful packages
-   Hands-on: advanced data manipulation

### 5. Generating visual outputs

This section will show participants how to (1) Create basic plots using base R functions; (2) Understand how to connect data frames with ggplot2; (3) create basic graphs with ggplot2; (4) use factors to customize graphics in ggplot2; (5) use RMarkdown to generate customized reports.

**Module content:**

-   Figures with base R
-   Graphics with `ggplot2`

### 6. Real life application: COVID testing dataset

This hands-on activity will familiarize participants with a real-life use of R in the pharma industry environment and encorage them to apply the knowledge from previous modules to create an analysis pipeline.

### 7. Software development concepts

To conclude the workshop, participants will (1) acquire good coding practices; (2) be familiar with code documentation standatds; (3) know what to avoid when programming in R; (4) learn how to debug and troubbleshoot their own code.

**Module content:**

-   Good coding practices\
-   Style guide\
-   Debugging and troubleshooting

## References

The materials for this workshop were based on the following sources:

-   [Base R Cheat Sheet](https://iqss.github.io/dss-workshops/R/Rintro/base-r-cheat-sheet.pdf)\
-   [Google's R Style Guide](https://google.github.io/styleguide/Rguide.html)
-   [Mastering Software Development in R](https://bookdown.org/rdpeng/RProgDA/)

*Workshop created as part of the McGill Initiative in Computational Medicine*
