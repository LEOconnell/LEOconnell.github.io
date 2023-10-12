# American Business Survey API
A project using data from  U.S. Census Bureau surveys.

A link to project README: [https://leoconnell.github.io/ABS-API-Vignette/](https://leoconnell.github.io/ABS-API-Vignette/)

## Background
This blog is about a project completed for NC State  ST-558, Data Science for Statisticians.  The purpose of the project was create a vignette demonstrating access to data via an API and subsequent exploratory data analysis.Specifically, the project includes steps to utlilize an APIs to access data, wrange the data into a usable form, and conduct a preliminary exploratory data analysis.  You can find this project on my repository called ABS-API-Vignette.  Additionally, the project was integrated with a GitHub repository from the start, enabling version control and publication in this environment. 

Here is a [link](https://github.com/LEOconnell/ABS-API-Vignette) to my repository. The name of the repository is ABS-API-Vignette.

## Project Summary
  This project represents an opportunity to explore several data science objectives including the use of an API, data wrangling and tidying, data analysis and presentation of workflow and results. The work for this project was completed in an R project, with results and work files posted in my repository. American Business Survey data from 2 endpoints was accessed and explored.

### API Commentary
The Census Bureau has excellent resources for developers including documentation, examples, and video demonstrations.  I found this data relatively easy to accces for a beginner such as myself!  The technical documentation includes extensive details on the survey methodology.  More about the nature of the survey data is included in the README.md file in the repository.  

### Programming Commentary
This project presented some programming challenges related to careful retrieval of data given the underlying dataset structure. Several functions were created using wildcard values allowed by the API, however this required careful wrangling to remove repeated totals in separate rows.  With more experience under my belt, a second pass at this project could yeild more sophisticated functions and analysis.

### Expoloratory Data Analysis Commentary
Survey data presents interesting challenges for summarization.  A significant effort was undertaken to sort through the underlying data structures to properly summarize the weighted data.  Some of these challenges presented themselves in terms of reflecting the weighted data properly in ggplot geoms.  A deeper dive into additional packages designed to specifically manipulate this type of data may aid this type of analysis but was not extensively investigated for this project.

Additionally, the aggregated survey data required careful wrangling and manipulation. I found it especially useful to view the data within the R environment frequently to ensure aggregations were handled appropriately.  

### Summarization of Data Analysis
The analysis relies on the North American Classification of Industry System (NCAIS). I have included a copy of an excel table that decodes this 2-4 digit NACAIS codes in my repository for reference.
Some of the  findings from this initial pass are unsuprising. However, one find that stood out when looking at the transportation industry, is that it appears that veteran owned family businesses may have higher payroll/employee expenses.  This could be worthy of further exploration. 



