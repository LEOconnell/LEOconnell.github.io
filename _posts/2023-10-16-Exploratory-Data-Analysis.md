# Exploratory Data Analysis

As part of the ST-558 Data Science for Statisticians course at NC State, several readings were reviewed to provide a basic understanding of the steps, methods, and overall objectives related to Exploratory Data Analysis (EDA). 

Based on background from these readings, I will try to answer 3 questions which essentially outline a basic strategy for EDA:
1. What is my overall goal when doing EDA?
2. What methods are important?
3. What things do I look for while doing EDA?

## The Art of the Science....
As many authors, professors and data scientists have commented, EDA is an art. I believe it is an art that is shaped by the methods and tools available to the evaluator.  That being said, as I work my way through formal study of statistical methods and EDA processes, I find myself refining my EDA skills. 

## Goals When performing EDA
EDA is the first step in turning data into insight.  With that in mind, my overall goals are to determine if the data is valuable to a specific research question. My specific objectives are to 1) understand the nature of the data in hand and 2) evaluate the data potential for yielding insight, such as in models for inference or prediction relevant to the research question.  
Examples of a broad research questions would be: 
- What factors influence sales of our companies product?
- Do different schools have different performance on standardized curriculums?
  - What factors contribute to the differences?"
 
EDA can be done using many tools using many methods. Below is a basic outline of my current EDA process that uses both numeric and graphical methods.

##  EDA Strategy

Based on the course readings and my experience to date, my strategy for conducting EDA is as follows:  

**Task 1: Understand the Research Question**  
It is important to understand the questions you are trying to answer. This will shape how you look at the data. Input from subject matter experts is important  and can guide the exploration.  I think it is valuable to have SME involved at multiple steps. In addition to their overall guidance, their contextual  knowledge may be helpful in explaining data anomalies molies or in selecting variables of interest.

**Task 2: Get to know the Data**  
a.	Know the nature of the data structure. For example does the data represent observations over time, cross-sectional, survey data, repeated test results, etc.  

b.	Understand the quality of the data. For example, is data missing? How were the underling values collected?  

c.	Explore the data elements. Does the data have relevant outcome and predictors variables? What formats are used to store data elements? Are there aggregations or estimates?  

d.  Clean and tidy the data to make is useful for exploration and statistical learning methods.  

**Task 3: Explore the Data Elements**  
a. Univariate Analysis: Look at variables individually. Find measures of center and spread. Determine if variables are categorical. Look for outlier values.  

b.  Bivariate Analysis: Begin to look at associations/relationships between variables of interest.  

##  Methods to Summarize Data Elements:

Several methods are valuable in EDA to describe: 

*Data Distributions*  
What type of distribution does each variable's values follow?  To understand this we can calculate the mean, standard deviation and quartile values for numeric variables. Histograms, frequency plots, and probability density plots are all useful here to visualize the data.

*Relationships*  
We hope to find underlying relationships when we perform EDA.  To that end, numeric methods that describe relationships such as correlation, covariance, are helpful. To visualize these relationships across numeric variables we can use scatterplots. Cross tabulations can provide insight into potential associations for categorical data.  Boxplots that show differences in response variables by categorical variables can also help visualize potential differences in responses varaibles at different levels of categorical variables. 

*Classifications*  
We may be interested in classification problems or clustering problems, and as such, understanding frequencies of observations by classification factors is helpful. 

##  Things to look for...
Several things should be noted while doing EDA.
- Data anomalies  and outliers should be identified to consider proper handling in further analysis.
- Opportunities to improve analysis of data through appropriate variable data transformations.
- Identification of variables that may have multicollinearity
- Evalute the data to see if it fits assumptions needed for planned models
- And most importantly, identification of variables of interest that may be useful as inputs to models for inference or prediction.
- Unexpected relationships! EDA is exploration - be open to finding the unexpected!
  





