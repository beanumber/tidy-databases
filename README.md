Databases in the tidyverse
================

The `dplyr` package within R provides a flexible and powerful syntax for
data wrangling operations. However, data objects within R are typically
stored in memory and performance issues may arise as data become large.
Database management systems implementing SQL (structured query language)
provide a ubiquitous architecture for storing and querying data that is
relational in nature. While there has been support for data retrieval in
R from relational databases such as MySQL, SQLite, and PostgreSQL,
recent advances that have added interfaces between R and SQL enable
users to seamlessly leverage storage and retrieval mechanisms while
remaining within R. In this webinar, we will review key idioms for data
wrangling within `dplyr`, introduce the backend interfaces for common
database systems, provide examples of ways that the `dplyr` engine
translates a data pipeline, and discuss common misconceptions and
performance issues.

  - Ben Baumer  
    Smith College Program in Statistical and Data Sciences

> Benjamin S. Baumer is an assistant professor in the Statistical & Data
> Sciences program at Smith College. He has been a practicing data
> scientist since 2004, when he became the first full-time statistical
> analyst for the New York Mets. Ben is a co-author of The Sabermetric
> Revolution and Modern Data Science with R, and won the 2016
> Contemporary Baseball Analysis Award from the Society for American
> Baseball Research.

  - Nicholas Horton  
    Amherst College Department of Mathematics and Statistics

> Nicholas Horton is Beitzel Professor of Technology and Society
> (Statistics and Data Science) at Amherst College, with methodologic
> research interests in longitudinal regression models, missing data
> methods, and statistical computing. He graduated from the Harvard TH
> Chan School of Public Health in 1999. Nick has received the ASA’s
> Founders Award, the Waller Education Award, the William Warde Mu Sigma
> Rho Education Award, and the MAA Hogg Award for Excellence in
> Teaching. He has published more than 170 papers, co-authored a series
> of four books on statistical computing and data science, and was co-PI
> on the NSF funded MOSAIC project. Nick is a Fellow of the ASA and the
> AAAS, served as a member of the ASA Board, chaired the Committee of
> Presidents of Statistical Societies and is the ASA Section on
> Statistical Education. He is a member of the National Academies of
> Sciences Committee on Applied and Theoretical Statistics and two
> Academy groups focused on data science education.

### Other resources

  - [Webinar
    slides](https://beanumber.github.io/tidy-databases/tidy_databases_slides.html)
  - [SQL
    Example 1](https://beanumber.github.io/tidy-databases/examples/sql-example1.html)
  - [SQL
    Example 2](https://beanumber.github.io/tidy-databases/examples/sql-example2.html)
  - [Setting the stage for data
    science](http://chance.amstat.org/2015/04/setting-the-stage/):
    integration of data management and databases in statistics courses
    (CHANCE 2015), also <https://arxiv.org/abs/1401.3269>
  - [Modern Data Science with R](http://mdsr-book.github.io/)
  - [R for Data Science](http://r4ds.had.co.nz/)
  - [Dplyr vignettes](http://dplyr.tidyverse.org/)

-----

### Acknowledgements

This work was partially supported by NIH grant 1R15DC014129-03
(<https://projectreporter.nih.gov/project_info_description.cfm?aid=8769352&icde=30039221&ddparam>).
More info can be found at: <http://www.science.smith.edu/wai-database/>

Last updated November 03, 2018
