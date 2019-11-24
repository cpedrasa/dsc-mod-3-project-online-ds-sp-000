
# Module 3 -  Final Project Specifications

Module 3 Final Project
Student name: Cynthia Pedrasa
Student pace: self paced
Scheduled project review date/time: November 27, 2019
Instructor name: Eli Thomas

### Jupyter notebook:    
https://github.com/cpedrasa/dsc-mod-3-project-online-ds-sp-000/blob/master/student.ipynb 

### Blog post URL:  
https://cpedrasa.github.io/module_3_project

### Executive Summary:    
https://github.com/cpedrasa/dsc-mod-3-project-online-ds-sp-000/blob/master/Mod3ProjCPedrasa.pdf

## Table of contents:

### Project Background

For this project, I will be working with the Northwind database--a free, open-source dataset created by Microsoft containing data from a fictional company. The goal of this project is to test the student's ability to gather information from a real-world database and use the knowledge of statistical analysis and hypothesis testing to generate analytical insights to answer the following question:

Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?

In addition to answering this question with a hypothesis test, the student will also need to come up with at least 3 other hypotheses to test on your own. These can by anything that you think could be important information for the company.

## Experimental Method: The Data Scientist would go to the following steps to conduct the experimental design to answer the business questions.

#### Making Observations: 
Northwind would like to administer pricing policies involving quantity discounts but the company's knowledge of these discounts is quite limited. Northwind recognizes that to be competitive, they need to meet customer expectations on quantity discounts and need data-driven decision-making in the development, implementation of a profitable discount schedule.

#### Examine the Research: 
The Data scientist will work with the Marketing Manager and other Business stakeholders to review the current best practice guidelines from the economics and marketing literature in the quantity discounts to understand the metrics for optimization. This step include the Data Science Framework iterative processes of obtaining the data, cleansing the data, exploring the data to understand the business problem/question and help finding the appropriate hypothesis test (test statistic) to use.

#### Form a Hypothesis: 
Before we run any hypothesis test, we need to specify the two hypotheses: the null hypothesis (H0) and the Alternate Hypothesis (Ha). we start by assuming the null hypothesis which is "there is no difference between the quantity of product ordered with discounts or without discounts and that what we're seeing is just random probability that the difference is due to chance versus not. We are interested in disproving the null hypothesis.

#### Conduct the Experiment. 
After we explored the data, formulated the hypothesis, and decided on the correct hypothesis test to use, we will execute the statistical test.

Analyze experimental results: looking at the data and understanding what happened after running the test statistic to determine if the test is statistically significant or not.

#### Draw conclusions: 
When we find strong enough evidence against the null hypothesis,(p value <= significace level) we reject the null hypothesis/the result is statistically significant. When we do not find evidence against the null hypothesis,(p value >= significace level) we fail to reject the null hypothesis/the result is not statistically significant.  

## I. Obtaining the Data

A. Import the Libraries  
B. Connect to the Northwind database  
C. Inspect the Data  

## II. Scrubbing the Data

A. Missing Values and Distinct Values  

## III. Exploring the Data

A. Descriptive Statistics  
B. Outliers Check  
C. Normality check  
D. Sample Size and Data type check  
E. Equal Variance check (Homoscedasticity)  
F. Independent sample check (Multicollinearity)  

## IV. Run the Statistical Test

A. Statistical Hypothesis Process  
B. Create a Sample Distribution of Sample Means (with replacement)  
C. Run the hypothesis test  
D. Effect Size and Statistical Power  
E. Is there a difference in the mean quantity between discount levels?  
F. Is there a difference in the mean quantity of order between product categories?  
G. Is there a statistically significant difference in discount between product categories?  
H. Is there a difference in the mean quantity of order between salesperson?  
I. Is there a difference in the mean Total Sales between Customer Country?  

## V. Interpret Findings  
Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?

+ **Discount has a significant effect on quantity ordered.**

What levels of discounts have a statistically significant effect on the quantity of a product in an order?   
+ There is enough evidence to support the claim that there is a difference in mean quantity of orders between discount levels. **5%, 15%, 20%, and 25% discount levels have a significant effect on quantity of product ordered.**  

We also looked at other features that may have an effect on quantity ordered and discount motivations such as product categories, salespersons granting discounts, and customers.  

There are certain products that are more strongly in the customer focus. Knowing these primary products will help set competitive price. Knowing your secondary products could gve you more flexibility with pricing. 



Is there a difference in the mean quantity of order between product categories?  
+ **There is NOT enough evidence to support the claim that there is a difference in mean quantity between product categories.**

Is there a difference in the mean quantity of order between product categories and discounts?
+ **There is NOT enough evidence to support the claim that there is a difference in mean quantity between product categories and whether or not a discount is applied.**

Is there a difference in the mean quantity of order between salespersons and whether or not discounts are applied?  
+ **There is NOT enough evidence to support the claim that there is statistically significant difference in average quantity of product ordered between salespersons.**

Is there a difference in the Average  Total Sales between Countries?  
+ **There is a statistically significant difference in the average TotalSales between customers from Austria & Argentina, Austria & Brazil, Austria & Finland, Austria & France, Austria & Italy, Austria & Mexico, Austria & Spain, Austria & UK, Austria & Venezuela. While Austria has the largest Total sales followed by Portugal, the test however didn't find a significant difference in the mean Total sales between these two countries.**


## Recommendation for Future Studies
I hope the findings above could provide a baseline information to help the Northwind Marketing Team in discount pricing  and help guide further exploration to determine where discounts has an effect in boosting volume of sales and profit. Further study is recommended to determine the variety of motivations for quantity discounts to help provide guidelines to the organization in designing quantity discount schedules and set out the most fruitful directions for future research.

While discounts significantly impact the quantity of products ordered and increase overall sales volume, it would be advantageous to understand  the true impact of giving a discount to ensure profitability when offering discount pricing. We recommend that other metrics impacting discount pricing methods be considered for future research.  

+ How can we identify customers with below-average margins? How could we segment discount offers to different types of customers (first-time, dormant, repeat) to entice new sales without losing out on the margins of sales?
+ What type of discount (e.g. volume discount, event or seasonal discount, free shipping) has a higher impact on the volume of sales? 
+ Analyze granted discount frequencies and how the Sales Team is using the full range of percentages to understand how to link discounts with sales incentives.  In addition to analyzing which salesperson sells the most, further focus on profit analysis is equally important.
+ Does giving a 20% discount mean the company has to sell 20% more product to make up for what the company gave away? How much more will Northwind need in sales volume to generate the same amount of gross profit dollars as before?
+ Is there enough market demand to generate 20 percent more sales with a 10% drop in price. Is the discount really necessary?

