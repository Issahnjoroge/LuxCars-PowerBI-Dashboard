#Luxcars power bi dashboard

## Project Objective
The objective of this project is to build an interactive Power BI dashboard for Luxcars Logistics to analyse car sales, revenue, customer behaviour an delivery performance across Kenya.

## How I imported the data into aiven

1. Created a postgreSQL  service on Aiven.
2. Downloaded the CA certificate from Aiven.
3. Installed the certificate on windows in the Trusted Root Certification Authorities stores.
4. Used DBeaver to connect to Aiven and imported the raw dataset.
5. Verified the. data was loaded successfully.

## How I connected Power BI to the database
1. Open Power BI.
2. Click get data to postgreSQL database.
3. Input the server and database.
4. Set the ssl mode.
5. Connect and load the table.

## The measures and calculations I used
The measures include;
1. Total revenue
2. Total Units Sold
3. Total Orders
4. Gross Profit
5. Gross Profit Margin
6. Avg Delivery Days
7. Avg Rating.
The calculations include;
1. Sum
2. Countrows
3. Divide
4. Average

## The visuals I include in my dashboard
1. Slicers
2. Pie chart
3. Bar chart
4. Column chart
5. Donut chart

## My key insight
1. Rift-Valley shows as the region with the highest total revenue while Mombasa was the lowest region.
2. Toyota as a car make made the highest sales while Volkswagen gave the lowest revenue.
3. Most cars that were ordered were delivered.
4. Most cars that were ordered were paid for.
5. The average delivery time was around 10 days.

## My recommendations
1. Stock more Toyotas since they generate the highest revenue.
2. Make the delivery be lesser days to maybe improve the customer rating.
3. Continue marketing SUVs as they are the top sellers.

## Tools that I used
1. Aiven
2. DBeaver
3. Power BI
4. Github


ARTICLE LINK 
https://dev.to/elizabeth_njoroge_7c850b9/-connecting-power-bi-to-sql-databases-3k7l

