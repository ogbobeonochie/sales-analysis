# sales-analysis
## onochie supermarket sales analysis

## Table Of Contents


- [Project Overview](#project-overview)

- [Data Source](#data-source)

- [Tools](#tools)

- [Data Cleaning Preparation](#data-cleaning-preparation)

- [Exploratory Data Analysis](#exploratory-data-analysis)

- [Data Analysis](#data-analysis)

- [Visualization Result](#visualization-result)

- [Results / Findings](#results-findings)

- [Insights](#insights)

- [Recommendations](#recommendations)

- [Limitations](#limitations)

- [Takeaways](#takeaways)

- [References](#references)


## Project Overview

This is a python and SQL project on an imaginary supermarket called onochies Supermarket
the analysis project objectives is to analyze and glean insight into the sales performance of onochie supermarket for the period of year 2011 to 2014.
By analyzing various aspects of the sales data, we want to identify trends, make data driven recommendation, 
and gain a deeper understanding of the supermarket's(company) performance to answer critical questions and help the supermarket make data-driven decisions. 
Disclaimer: All dataset and reports here do not represent any company,
institution or state but just a dummy dataset to demonstrate the power of python and SQL in data
analysis

  ## Data Source

  sales data: the primary dataset used for this analysis is the 
  "sales_data.csv" file, containing detail information about
  each sale made by the supermarket for the period under review.

  ## Tools

  - Excel

  - Python Data Analysis

  - SQL

  ## Data Cleaning Preparation

  
  in the initial data preparation phase,I performed the following tasks:

    1.Data Loading and Inspection 

    2.Handling missing values 

    3.Data cleaning and formatting 

  ## Exploratory Data Analysis

  EDA provides the means to exploring the sales data to answer critical questions such as:

  - What is the overall sales trend?

  - Which products are top sellers

  - what are the peak sales period?

  ## Data Analysis

  ```python

  some interesting codes/features worked with (use backtick)

```
  
  ```python
  
  df = pd.read_excel("C:\\Users\\HP\\Downloads\\superstore_sales.xlsx")
  ```

  ```python
  sales.columns = [i.lower()for I in sales.columns]

```

  ```sql
  select * from sales
```

# Visualization Result


![visual](https://github.com/user-attachments/assets/2243e01c-e3ef-4908-b803-3d86301807ca)

  ## Results Findings

  The following are the summary of the analysis:

     1.The supermarket sales has been steadily increasing over the past year,
     with noticeable peak during the holiday seasons

     2.Product category Apple smart phone,Cisco Smart Phone,Motorola Smart Phone,Nokia Smart Phone,
     Canon Image CLASS 2200 Advanced Copier,Hon Executive Leather Armchair Adjustible, Office Star Executive Leather 
     Armchair,Harbour Creations Executive Leather Armchair Adjustible,Samsung Smart Phone and
     Nokia Smart with Caller ID are the best performing 
     category in terms of sales and revenue generation
     
     3.Customer segment with live time value (LTV) should be targeted for 
      making efforts

  ## Insights

  This analysis provides valuable insights into the company's sales trend

   - The seasonal pattern suggests that the company's sales are influenced by external factors such as holidays,weather or economic conditions

   - The consistent peak in sales during November and December indicates a strong holiday season demand

   - The drop in sales in January may be due to post-holiday season slump 

  ## Recommendations

  
   Based on the just concluded analysis, we here by recommended the 
   following actions:

   - Developing targeted marketing campaigns to capitalize on holiday season demand 

   - Analyzing external factors,suchas weather or economic conditions to better understand their impacts on sales 

   - Exploring strategies to mitigate the post-holiday season slump in January

 ## Limitations

 
    I have to remove all missing values and filling them with zeros in al the columns 
    because they would have impacted the accuracy of my result or conclusion from 
    the analysis. There are still a few outliers even after the verification but even then 
    we can still see that there is positive correlation between Monthly and Yearly sales and products

 ## Takeaways

    This project demonstrates the importance of time series analysis in understanding sales trends and informing businesss decisions.
    By leveraging data analytics and visualization techniques,businesses can gain insights 
    into their sales performance and make data-driven decisions to drive growth 

 ## References

 - SQL GUIDE for beginners by warty

 - Stack overflow

 - Konga website  






  







  


 
