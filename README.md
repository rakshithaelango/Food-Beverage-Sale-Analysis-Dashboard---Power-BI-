# Food-Beverage-Sale-Analysis-Dashboard---Power-BI

## INTRODUCTION
* This project is aimed to develope powerBi Dashboard for Food and Beverage Sales Analysis

## STEPS IN DETAIL
* Install And Load powerbi Data.
  
* Data cleaning.
  
    * Removing columns.
    * Changing data types.
    * Changing null values.
      
* Data preprocessing.
  
* Data modelling.
  
* Dashboard creation Created Dashboard.

   * Cards: Created cards to show Total Revenue, Orders, ATP.
   * Fliters: Created Fliters to show Quater, Channel, Productcategory.
   * Tables: Created to visualize Orders, total Revenue, ATP.
   * Charts: Created to visualize Revenue / Salespersons, Orders / Salespersons, Revenue and orders / Quater And Revenue / productgroup.
     
* Dashboard Visual:
   
![1693648534378](https://github.com/rakshithaelango/Food-Beverage-Sale-Analysis-Dashboard_Power-BI-/assets/116090323/51815279-6e42-4e81-a91d-00772e8823fb) 

* DAX MEASURES USED FOR KPI:

   * Revenue = sum(Sheet1[Sales_Amount])

   * Orders = DISTINCTCOUNT(Sheet1[OrderNumber])

   * Average_Ticket_Price = DIVIDE('Product'[Revenue],'Product'[Orders],"")
