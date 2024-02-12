# avocado-dataset-data-analysis-ms-excel
INTRODUCTION 

Avocando is an avocado online store based in the USA. They have been in operation since 2015. The co-founders Elizabeth Martinez and Jessica Levy are both thinking of improving their company by expanding their product line and marketing strategies. They would like to connect more with customers by understanding customer insights and trends in the avocado market with the aim of serving their customers better. They would like to understand what are the top avocadoes sold and the prices and what influences these sales. Ultimately, the goal is to expand their market reach online. We will need to come up with some recommendations on how they can improve Avocando for the upcoming year.

PREPARING DATASET 
The avocado prices public dataset is used for this analysis. It explores historical data on avocado prices and sales volume in the US. This dataset is public and provided by the Hass Avocado Board. It contains all the necessary data for this analysis.

Some relevant columns in the dataset:

Date - The date of the observation
AveragePrice - the average price of a single avocado
type - conventional or organic
year - the year
Region - the city or region of the observation
Total Volume - Total number of avocados sold
4046 - Total number of avocados with PLU 4046 sold (Small/Medium Hass Avocado (~3-5oz avocado) | #4046 Avocado)
4225 - Total number of avocados with PLU 4225 sold (Large Hass Avocado (~8-10oz avocado) | #4225 Avocado)
4770 - Total number of avocados with PLU 4770 sold (Extra Large Hass Avocado (~10-15oz avocado) | #4770 Avocado

The aim is to analyze the dataset with the help of a pivot table and data visualization using MS EXCEL.

  1. For the given dataset, the country is been added which will help us in further analysis.
 
  2. Finding the revenue of the avocado product: formula is - (avocado price * total number of avocados sold)
       ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/573c50d4-ff58-4fa6-97a0-8b662f26a029)

  3. Finding the descriptive analysis for certain parameters
       ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/1b41080d-dba3-4f26-8423-689d95a44f85)

     This infers the statistical analysis for the Average price of an avocado
     
  4. Sampling :

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/d33d32fe-9b06-4bb5-b561-77ae9bbc35cf)
   
      For understanding the concept of sampling, Sampling is the process of selecting a subset of elements from a larger population in order to make inferences or draw conclusions about the entire population.
      There are multiple types of sampling. Random sampling involves selecting elements from a population entirely by chance, with each element having an equal probability of being chosen.
       Periodic sampling, or systematic sampling, involves selecting elements from a population at regular intervals or fixed periods.

  5. To calculate the top 10 average prices of avocados over the different regions in the year 2015

       ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/3dfcb1f5-49d5-4e45-a875-014daae66f03)

     This analysis is inferred by adding the average price in the value column and region in the rows of the pivot table. The highest average price is also visualized by a bar graph which indicates that Hartford Springfield has the highest average price of avocados.
 
  6. Analyze the seasonal patterns in avocado prices. Create  charts or area charts to visualize how prices fluctuate throughout the year.  

     ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/cb9baa8c-650e-4bbc-a145-3d10ea01ab25)

     ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/59ec1f09-cb3f-41d7-bcbf-ad3fb868122d)


  This infers that 540 is the highest average price of avocados which were sold in March, May, Nov of 2015, Jan, May, Oct of 2016, Jan, Apr, July, Oct of 2017 

  7. Trends of avocado sales volume

     ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/1628c6f2-3a6e-473e-88f9-1ace9fe67d1f)

      this analysis infers 2017 has the highest sales volume and 2018 has the lowest sales volume.

  8. Compare the average prices of organic and conventional avocados. Use conditional formatting to highlight the differences.

       ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/d84f5e28-919a-447c-8496-a59bddcf625a)

        ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/04a584f5-4c0a-4c43-842d-260039ae6bf2)

     This can be concluded that the average price of organic avocados is higher than the conventional type of avocado.

  9. Explore how avocado prices vary across different regions. Create charts or tables to display the regional price differences.

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/70218494-ce9e-4c09-b18d-ed1677b65808)

      With the help of a bar plot and pivot table, also with the top 10 regions that had the top average price of avocados sold, San Franciso had the highest average price of avocados sold.

  10. How many small bags of conventional type of avocados are sold in the year 2016 and 2018?

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/457ba14f-d1b9-402d-ad81-3b680cc67c2d)

      This infers that 2016 has the highest number of small bags of conventional type of avocados sold.

  11. Which year has the highest number of total bags sold?

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/3103e467-490e-4263-8629-72f793b59bc5)
    
      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/8fec478a-8b0a-4f7b-a5fc-3abca6881467)

      This infers that the 2017 year had the highest total bags sold.

  12. What is the correlation of small bags with the large bags of avocados sold?

        ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/b72a7f65-8916-453d-b28c-ad5f80623704)

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/e2ef6918-6b66-402c-9a1c-2fdb3b9e14c7)

      This is a positive correlation between small bags and large bags.

  13. What is the overall distribution in average avocado prices over the years?

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/cea75728-c4a6-4c7e-8699-acb23b251476)

      This infers that in 2018, there was a high sale of avocado.

  14. Which region had the highest total avocado sales volume?

        ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/5dd64ebd-c424-42ee-844b-9607142691b3)

       This infers that the TotalUS region had the highest total avocado sales.

  15. Are there any correlations between the average price and the total volume of avocados sold?

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/d2c17e16-7efd-4057-bfa6-1764506ea0e9)

      This infers that there is a negative correlation of -0.192752387152719 between average price and total volume of avocados sold.

  16. Are there any noticeable trends in the total number of avocados sold for each type over 2015 and 2016?

      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/ef0bca73-b600-440b-b922-554ac2d8858c)

      This infers that more conventional types of avocados are sold in 2015 and 2016.

  17. Identify and rank the top regions in terms of avocado production. Use Pivot Tables and charts to present the data.
 
      ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/29c28f2a-ec14-4888-a04a-7b6d6861716d)

        This analysis infers that the Plains region has the highest avocado production.

  18. Which type of avocado and in which month has the highest sales of avocado in 2017?

        ![image](https://github.com/sahanavenkatesh242/avocado-dataset-data-analysis-ms-excel/assets/157820520/4370eaea-638a-4a02-b02f-d9f0dbd27808)



       This infers that the conventional type of avocado in January was sold at the highest volume.



This analysis is performed using Microsoft Excel, and no additional libraries or tools are required.





