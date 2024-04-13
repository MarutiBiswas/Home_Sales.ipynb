# Home_Sales: this challenge, we use our knowledge of SparkSQL to determine key metrics about home sales data. Then we use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
![4DB3420F-E78F-483A-BFC9-DD1D4B84CBBD_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/b4b77c71-6f89-4163-9b89-cd1f3ae3bd30)

First change the data types then sql query for the answers.

![B9DBADAD-62F6-4E8E-BEA0-35C072543CFD_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/70c378be-9a13-4d1c-ba88-89949a957fc1)

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places. The average prices for a four bedroom house sold by year are as follows:

![9F3E6321-0616-47EB-9525-6E8C7D56D8B4_4_5005_c](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/e13dcd17-c0b6-45c8-bb9d-ec869b8a6797)

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![FA485BB8-9C80-4F0C-90EF-6F8FEC8F48E6_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/ec4b8704-6212-4352-b410-ca07e42534fd)

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![C444A1B4-A813-4FB3-A61A-0E6052671065_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/0aa8d36c-a466-4afa-aae2-7fdd8d2b543b)

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![E97FC6FC-6F34-41F9-9858-CE9C60B60FFC_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/8a339820-860b-4929-8fff-0c3b6d163402)

![C50022A9-C221-4648-86C7-B3CB67462F9A_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/7a267047-e794-449e-b1bd-618f80dd761b)

![E1B51DB0-2B16-4876-9FA1-535F7F428D91_1_201_a](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/23423451-0d3d-4816-a73a-a027ac25fdbc)

Compare the run times for the various methods of running the same sql query as question :

![3AF3BC85-D2DE-4B05-A2D3-B1925DE12856_4_5005_c](https://github.com/MarutiBiswas/Home_Sales.ipynb/assets/147889069/0323e218-04fa-43a3-9483-c7eedfae43dc)


The highest run time was the sql query from the partitioned parquet files (1.4958586692810059 seconds). It was 0.86934 seconds slower than the cached temporary table sql query (0.62650895511871338 seconds) and 0.84655 seconds slower than the original temporary table view sql query (0.6493072509765625 seconds). The cached temporary table sql query runs fast 0.02279 seconds faster than the original temporary table query.


