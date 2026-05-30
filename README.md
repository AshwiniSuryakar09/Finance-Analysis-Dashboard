# Finance-Analysis-Dashboard


OVERVIEW ANALYSIS : -


   ![Finance-Analysis-Dashboard -Overview Analysis](https://github.com/AshwiniSuryakar09/Finance-Analysis-Dashboard/blob/main/dashboard%201.png)



TRANSACTIONS : -


   ![Finance-Analysis-Dashboard -Transactions](https://github.com/AshwiniSuryakar09/Finance-Analysis-Dashboard/blob/main/Dashboard%202.png)



## 🧾 Project Overview


  The Finance Analysis Dashboard is an interactive Power BI solution designed to analyze financial transactions, customer behavior, transaction performance, and revenue-related metrics. 
  The report consists of two interconnected dashboards:

  Overview Analysis Dashboard – Provides high-level financial insights and KPI tracking.
  Transaction Analysis Dashboard – Provides detailed transaction-level information with drill-through capabilities.

  The dashboard enables users to dynamically analyze Total Amount, Total Transactions, Total Fees, and Total Tax across different dimensions such as year, occupation, customer segment,       transaction status, gender, state, and transaction type.




>  ## 📌Dashboard 1: Overview Analysis

  
  Objective

  The Overview Analysis dashboard provides a comprehensive view of financial performance through dynamic KPIs and interactive visualizations. Users can instantly switch between different business metrics and understand trends, customer behavior, and transaction performance.



> ### Interactive Filters (Slicers)

The dashboard includes multiple filters to allow detailed analysis:


*  1 .  Year Filter

   Allows users to select a specific year for analysis.

   All KPIs and visualizations update automatically based on the selected year.






*  2 .  Dynamic Metric Selector


   One of the key features of this dashboard is the Dynamic Metric Selector.

   Users can switch between:

       1.Total Amount
    
       2.Total Transactions
    
       3.Total Fees
    
       4.Total Tax

    All charts, KPIs, and visualizations update dynamically according to the selected metric.

    This eliminates the need to create separate pages for each metric and provides a highly interactive user experience.





*  3 .  Occupation Filter


    Allows analysis based on customer occupation categories such as:

       1. Business Owner
    
       2. Salaried
    
       3. Student
    
       4. Self-Employed
    
       5. Others

    Users can identify which occupation contributes the most to selected financial metrics.





*  4 .   Category Filter


    Allows users to analyze data based on transaction categories such as:

       1. Bank Charges
   
       2. Shopping
   
       3. Education
   
       4. Fuels
   
       5. Groceries
   
       6. Travel
   
       7. Utilities
   
       8. Insurance
   
       9. Healthcare

       10.Mutual Fund





 1. Total Amount KPI


     Displays :

     Total transaction amount
   
     Year-over-Year comparison

       Percentage Change Formula: (Current Year - Previous Year )/ Previous Year * 100 


     Positive growth is displayed with a "+" sign.

     Negative growth is displayed with a "-" sign.







 2. Total Transactions KPI


     Displays :

     Total transaction count
   
     Comparison with previous year







 3. Average Transaction Value KPI


     Displays :

     Average amount per transaction.







 4. Total Fees KPI


     Displays :

     Total collected fees







 5. Total Tax KPI

    Displays :

    Total tax amount
   
    Comparison with previous year
 
    Year-over-Year comparison






> ###   Visualizations




1. Monthly Trend Analysis (Line Chart)



   Purpose  : - Shows monthly performance of the selected dynamic metric.


   Dynamic Behavior
   
   Based on metric selection :


   * 1.Total Amount by Month
     
   * 2.Total Transactions by Month
   
   * 3.Total Fees by Month
   
   * 4.Total Tax by Month


   
    Business Insights

    Users can identify :

    * 1. Seasonal trends
 
    * 2. Peak transaction periods
 
    * 3. Revenue growth patterns
 
    * 4. Monthly performance fluctuations







   

2. Transaction Status Analysis (Pie Chart)


    
   Purpose : - Displays metric distribution by transaction status.

   Statuses include:

         1 . Success
   
         2 . Failed
   
         3 . Pending

    
   Dynamic Behavior : - Changes according to selected metric.

   Insights

   Helps identify:


   * 1 . Successful transaction contribution
   
   * 2 . Failed transaction impact
   
   * 3 . Pending transaction volume









3. Customer Segment Analysis (Bar Chart)


    
    * 1 . Segments
   
    * 2 . Retail
   
    * 3 . SME
   
    * 4 . Premium
   
    * 5 . Wealth
   
    * 6 . Corporate    



   Dynamic Analysis : - Displays selected metric by customer segment.


   Business Insights


     Identifies:

     1 . Highest contributing customer segment
   
     2 . Segment-wise financial performance
   
     3 . Revenue concentration







4. State-wise Analysis (Bar Chart)


      
   Purpose : - Displays selected metric across different states.


   Examples:   Maharashtra  , Karnataka  ,   Gujarat  ,    Tamil Nadu ,   Haryana    ,    West Bengal

  
   Dynamic Behavior : - Metric changes according to selection.


   Insights


   Helps identify :


    1 . Top-performing states
  
    2 . Regional transaction distribution
  
    3 . Revenue contribution by state

    4 . Transaction Type Analysis (Matrix/Table)



    Purpose : - Provides detailed financial breakdown by transaction type.



    Transaction Types include :

  
     1 . Bill Payment
  
     2 . Metrics Displayed



    For each transaction type :


     1 . Amount
   
     2 . Fees
   
     3 . Tax
   
     4 . Transactions Count




> * Conditional Formatting : - Conditional formatting has been applied to improve readability and performance interpretation.



   * Benefits :-


     1 . Easy identification of high-value transaction types.
   
     2 . Quick comparison across categories.




 
 6. Gender Analysis (Donut Chart)

   
  Purpose : - Displays selected metric distribution by gender.


  Categories :
  
   1 . Male
       
   2 . Female


  Dynamic Analysis : - Changes according to selected metric.


  Examples:


   1 . Total Amount by Gender
 
   2 . Total Transactions by Gender
 
   3 . Total Tax by Gender
 
   4 . Total Fees by Gender


 
   Insights : - 


   * Allows understanding of customer contribution by gender.
   
   * Enhanced user experience.






> # Dashboard 2: Transaction Analysis


   Objective  : - The Transaction Analysis dashboard provides detailed transaction-level records and enables users to investigate individual transactions.


   Filters Available



   Users can filter transactions by : -


   1 . Year
   
   2 . Dynamic Metric
   
   3 . Occupation
   
   4 . Category

   All selections from Dashboard 1 can be carried into Dashboard 2.



   KPI Cards : - The same KPI structure is maintained for consistency.


   1 . KPIs Included
   
   2 . Total Amount
   
   3 . Total Transactions
   
   4 . Average Transaction Value
   
   5 . Total Fees
   
   6 . Total Tax



  Each KPI includes  :

   * Current value
   
   * Previous year comparison
   
   * Positive/Negative percentage change






 >  *  Transaction Detail Table


   The central component of Dashboard 2 is the detailed transaction table.

   Columns Included : - 
   
   1 . Transaction ID
   
   2 . Transaction Date
   
   3 . Customer Name
   
   4 . Customer ID
   
   5 . Transaction Type
   
   6 . Gender
   
   7 . Customer Segment
   
   8 . Amount
   
   9 . Fees
   
   10 . Tax
   
   11 .Transactions




  ##  Purpose


   Allows users to :


   1 . Analyze individual transactions
   
   2 . Validate summary KPIs
   
   3 . Investigate anomalies
   
   4 . Review customer activity




> ### Drill-Through Functionality



 A major feature of this dashboard is the implementation of Drill-Through Analysis.


 How It Works


 Users can :

   1 . Right-click any visual.
   
   2 . Select Drill Through.
   
   3 . Navigate to detailed transaction records.






> ### Drill-Through Available Across Visuals

Users can drill through from:

  1 . Customer Segment Chart
 
  2 . State Analysis Chart
 
  3 . Transaction Status Chart
 
  4 . Gender Analysis Chart
 
  5 . Transaction Type Table
 
  6 . Monthly Trend Chart


> * Benefits

  Provides :

   1 . Detailed investigation of summarized values
   
   2 . Root cause analysis
   
   3 . Faster business decision-making
   
   4 . Improved data transparency





 
> * CSV Export Functionality

 Users can export transaction details directly from visuals.

 Features
  
   1 . Export filtered data
  
   2 . Export drill-through results
  
   3 . Export transaction-level records







 > ###  Key Power BI Features Used

   *  Data Modeling
   
   *  Star Schema Design
   
   *  Fact and Dimension Tables
   
   *  Relationships Management
   
   *  DAX Measures






> ### Implemented advanced DAX calculations for :-

   * Dynamic Metric Selection
   
   * Previous Year Comparison
   
   * Growth Percentage Calculation
   
   * Average Transaction Value
   
   * Dynamic Titles
   
   * Dynamic KPI Cards


   
> ## Interactive Features
   
   * Slicers
   
   * Drill Through
   
   * Dynamic Titles
   
   * Conditional Formatting
   
   * Cross Filtering
   
   * CSV Export





> ## Business Value

  This dashboard helps stakeholders :

   1 .  Monitor financial performance.
  
   2 .  Analyze transaction behavior.
  
   3 .  Track year-over-year growth.
  
   4 .  Identify high-performing customer segments.
  
   5 .  Understand regional performance.
  
   6 .  Investigate transaction-level details.
  
   7 .  Export filtered transaction records for further analysis.
  
   8 .  Make data-driven business decisions through interactive reporting.
  
   9 .  Tools & Technologies
  
   10 . Power BI Desktop
  
   11 . Power Query
  
   12 . DAX (Data Analysis Expressions)
  
   13 . Data Modeling
  
   14 . Interactive Visualizations
  
   15 . Drill Through Analysis
  
   16 . Conditional Formatting






  ## Conclusion

   The **Finance Analysis Dashboard** provides a comprehensive and interactive platform for monitoring financial transactions, customer activity, and business performance. By combining    dynamic KPI tracking, year-over-year comparisons, and detailed transaction analysis, the dashboard enables users to quickly identify trends, measure growth, and uncover actionable   insights.


  The **Overview Analysis Dashboard** offers a high-level summary of key financial metrics such as Total Amount, Total Transactions, Average Transaction Value, Total Fees, and Total Tax, while allowing users to dynamically switch between metrics and analyze performance across transaction status, customer segments, states, occupations, categories, and gender. The inclusion of previous-year comparisons helps stakeholders evaluate business growth and performance over time.


  The **Transaction Analysis Dashboard** complements the overview by providing detailed transaction-level records, enabling users to investigate individual transactions, validate summarized insights, and perform root-cause analysis through drill-through functionality. The ability to export filtered data and drill-through results further enhances reporting flexibility and supports external analysis requirements.


 Overall, this solution transforms raw transaction data into meaningful business insights, helping organizations:

  * Monitor financial health and operational performance.

  * Track year-over-year growth and performance trends.

  * Understand customer and regional contribution patterns.

  * Analyze transaction behavior across multiple dimensions.

  * Investigate detailed records through drill-through analysis.

  * Support data-driven decision-making with interactive reporting.

 By leveraging **Power BI, advanced DAX calculations, dynamic measures, conditional formatting, drill-through navigation, and export capabilities**, this dashboard delivers an  efficient, scalable, and user-friendly financial analytics solution for both strategic and operational decision-making.


