# Happy Mart Sales-Dashboard

### Dashboard Link: https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

There is a shop whose name is Happy Mart that wants us to help them create an interactive Dashboard so, they can easily track and analyze their online sales for the year 2018. This dashboard helps them understand their customers better. It helps the shop know which mode of payment is preferably used by their customers. They also know how much profit and loss they have in 2018 and other information. Thus, by using this dashboard they have identified or able to track their online sales and make good decisions for their better growth.


### Steps followed 

- Step 1: Open the Power BI desktop to Load data into the Power BI Desktop, datasets are CSV files.
- Step 2: Open the power query editor and import the CSV file in the editor to check or transform the data.
- Step 3: Close and apply the changes in datasets to go to the Power BI (Report View) interface.
- Step 4: Goes to Model View to establish the connections or relationship between the datasets based on common columns (attributes) for creating a report based on them.
- Step 5: Added Gradient Background to the dashboard & created a Shop name Heading (Happy Mart Sales Dashboard) by using Text Box.
- Step 6: I've created four measures i.e. Total Amount, Total AOV(Average Order Value), Total Profit, and Total Quantity.
- Step 7 : Measures:
        
        Total Amount:- 
        Total Amount = SUM(Details[Amount])

        Total AOV:-
        Total AOV = SUMX(Details,DIVIDE(Details[Amount],Details[Quantity]))

        Total Profit:-
        Total Profit = SUM(Details[Profit])

        Total Quantity:-
        Total Quantity = SUM(Details[Quantity])

- Step 8: Added four Cards that contain measures value i.e. Total Amount, Total Profit, Total Quantity, and Total AOV.
- Step 9: A bar chart was also added to the report design area representing the Top 5 states based on sales Amount. while creating this visual I've used filters option for filtering Top 5 states.

- Step 10: A Donut chart was also added to the report design area representing the percentage of Main Categories(Electronics, Furniture, and clothing) based on the quantity sold.

- Step 11: A Stacked column chart was also added to the report design area representing the Profit-loss by month for the year 2018. 

- Step 12: A column chart was also added to the report design area representing the Top 5 customers who placed frequent orders in the year 2018. while creating this visual I've used filters option for filtering Top 5 Customers.

- Step 13: A Donut chart was also added to the report design area representing the percentage of Mode Of Payment used by customers while placing an order.

- Step 14: A bar chart was also added to the report design area representing the Profit earned by the Top 5 sub-categories based on Sales Amount. while creating this visual I've used the filters option for filtering the Top 5 sub-categories.

- Step 15: In the report view, I've added two slicers:
        - The first one is based on Quarters which filters the visuals based on quarters. I have used tiles style in this.  
        - The second one is based on States which filters the visuals state-wise. I have used the Dropdown style in this.


Snap of Cards used in Dashboard,
-
- Total Amount

![TotalAmtCard](https://github.com/adorable20/Happy_Mart_Sales_Dashboard/assets/87119559/93eb71a1-fab1-49ea-b5c3-13f00bdeb6a2)

- Total Profit

 ![TotalProfitcard](https://github.com/adorable20/Happy_Mart_Sales_Dashboard/assets/87119559/10a06a79-05c9-4a62-bf4a-c97d690fef7d)  

- Total Quantity

![TotalQtycard](https://github.com/adorable20/Happy_Mart_Sales_Dashboard/assets/87119559/4f7911ad-84a5-41b6-b0d9-b77ee11e118e)

- Total AOV
 ![TotalAOVcard](https://github.com/adorable20/Happy_Mart_Sales_Dashboard/assets/87119559/ab8056d2-e1d7-41e7-a240-bfd09ee1caf3)   
