
# Amazon Superstore-Dashboard

### Dashboard Link :https://app.powerbi.com/reportEmbed?reportId=242f35a9-2dcc-4174-805a-50d4cdbe5e20&autoAuth=true&ctid=8d7b5b23-182d-4b77-9dea-a0821c7073c1

## Problem Statement

This dashboard helps the Business owner to understand their customers better. it helps to understand the segments of their products which segment perform better.

It helps to understand on which market the products perform better
It helps to understand on which region they perform better. 

Also it helps to understand Top-5 products according to sales and 
Bottom-5 products according to sales  


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : created a new column Delivery_Date.
- Step 4 : changed the Data type type of the columns.
- Step 5 : created a new column year to extract the year from the date table(use Date.year function). 
- Step 6 : Replaced the text values into numeric value.
- Step 7 : Since the data contains lots of null values . we removed the null values.
- Step 8 : pie chart|donut chart|stacked bar chart column chart were added.
- Step 9 : added clustered Bar chart and use Formatting Report.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : Added Slicers and Card's and logo
 
        
Snap of year wise sales Slicer ,

![Screenshot 2024-10-08 000434](https://github.com/user-attachments/assets/8273a978-18f4-48fb-8678-6b5778136143)

        


        
A card visual was used to represent sales projection.
![Screenshot 2024-10-08 001734](https://github.com/user-attachments/assets/b6939313-19f2-4915-954a-b9198c5ca9ae)

 
 
 A pie chart is used to visualize the sales by segment.
 

 
![Screenshot 2024-10-08 000644](https://github.com/user-attachments/assets/fa12c201-053a-4b20-8a6e-28149be33d9a)

 

    
 A donut chart is used to visualize the sales by market.
 
 
![Screenshot 2024-10-08 000701](https://github.com/user-attachments/assets/9ef6defb-9f14-4c87-b57f-ce8c629dd9fe)

A clustered bar chart is used to visualize the Top-5 and Bottom-5 products by profit

![Screenshot 2024-10-08 000740](https://github.com/user-attachments/assets/d3d3654c-e576-4709-8b98-8a6384a3521b)
![Screenshot 2024-10-08 000750](https://github.com/user-attachments/assets/2c4d6dbd-8acd-4f73-8415-b491925bfd8b)

 
 - Step 11 : The report was then published to Power BI Service.
 
 

# Snapshot of Dashboard (Power BI Service)

![Screenshot 2024-10-08 003253](https://github.com/user-attachments/assets/d17de1ca-277b-4a36-9634-2f0528ecd4a1)


 
 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot 2024-10-08 003112](https://github.com/user-attachments/assets/93263d92-cec3-430a-be84-f097c1bf5d28)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Sales in 2012 = 2.26M

   Total product unit in 2012  = 3022

   Total number of product returned in 2012 =  368

           
### [2] Sales By Segment in Year 2012

    a) Consumer Segment - 51.94%
    b) Corporate Segment - 30.61%
    c) Home Office Segment - 17.44%
   
  
  These Numbers will change if different Year filters will be applied.  
  
  ### [3] Sales By Market 
  
      a) Asia Pacific - 31.59%
      b) Europe - 23.93%
      c) USCA - 21.81%
      d) Latam - 17.04%
      e) Africa - 5.63%

These values will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Top- 5 Products by profit
 
 1.1) Ibico EPK-21 electric binding system(profit- 4630.48).
 
 1.2) Cisco Samrt Phone (profit-4066.86).
 
 1.3) Nokia Samrt Phone, cardless(profit-3880.19).

 1.4) Samsung Smart Phone VOIP(profit-3414.31)

 1.5) Nokia Smart phone , full size(profit-3332.46)
 
         thus, maximum profit from technology category.
 
 
