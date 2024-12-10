# sales-analysis
## onochie supermarket sales analysis

## Table Of Contents


- [Project Overview](#project-overview)

- [Data Source](#data-source)

- [Tools](#tools)

- [Data Cleaning Preparation](#data-cleaning-preparation)

- [Exploratory Data Analysis](#exploratory-data-analysis)

- [Results / Findings](#results-findings)


## Project Overview

This is a python and SQL project on an imaginary supermarket called Nasa Supermarket
the analysis project objectives is to analyze and glean insight into the sales performance of Nasa supermarket for the year 2023 .By analyzing various aspects of the sales data, we want to identify trends, make data driven recommendation, and gain a deeper understanding of the supermarket's(company) performance to answer critical questions and help the supermarket make data-driven decisions. 
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

    .Data cleaning and formatting 

  ## Exploratory Data Analysis

  EDA provides the means to exploring the sales data to answer critical questions such as:

  -What is the overall sales trend?

  -Which products are top sellers

  -what are the peak sales period?

  ## Data Analysis

  ```python

  some interesting codes/features worked with (use backtick)

```
  
  ```python
  
  sales_df = pd.read_csv("C:/Users/Nasa/Databankanalysis/Dataframes/sales.csv")
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

     2.Product category cloths,sockets and phones are the best performing 
     category in terms of sales and revenue generation
     
     3.Customer segment with live time value (LTV) should be targeted for 
      making efforts

  ## Recommendations

  
   Based on the just concluded analysis, we here by recommended the 
   following actions:

   - Invest in marketing and promotions during peak sales seasons to 
     maximize revenue

   - Focus on the expanding and promoting products categories  cloths,
     sockets and phones

   - Implement a customer segmentation strategy to target high LTV customers 
     effectively

 ## Limitations

 
    I have to remove all missing values and zeros from Tuesday to Friday columns 
    because they would have impacted the accuracy of my result or conclusion from 
    the analysis. There are still a few outliers even after the verification but even then 
    we can still see that there is positive correlation between daily sales and products 

 ## References

 - SQL GUIDE for beginners by warty

 - Stack overflow

 - Konga website  






  







  


 
