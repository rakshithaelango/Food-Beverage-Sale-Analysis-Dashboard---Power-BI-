# Food-Beverage-Sale-Analysis-Dashboard---Power-BI

## INTRODUCTION
* This project is aimed to develope pPowerBi Dashboard for Food and Beverage Sales Analysis

## STEPS IN DETAIL
* Install And Load powerbi Data.
  
* Data cleaning.
  
* Data preprocessing.
  
* Data modelling.
  
* Dashboard creation.

DAX MEASURES USED FOR KPI:

* Revenue = sum(Sheet1[Sales_Amount])

* Orders = DISTINCTCOUNT(Sheet1[OrderNumber])

* Average_Ticket_Price = DIVIDE('Product'[Revenue],'Product'[Orders],"")
