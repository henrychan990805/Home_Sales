# Home Sales Analysis Report
This project aims to use spark SQL to analyze home_sales dataframe to answer the following questions.
* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
<br>
Afterwards, this project will contrast the running time of ordinary, caching the data and parqueting the data.

## Results
### Overview of Original home_sales dataframe
![Overview](https://github.com/henrychan990805/Home_Sales/blob/9b28a59e6dfe0ba5989b5f0c36afa5ff3d065eec/Screenshots/OriginalDataFrame.png)
### Questions and Answers
#### Q1: What is the average price for a four-bedroom house sold for each year?
![4BPrice](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_4B_sort_by_year.png)
#### Q2: What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 
![3B3BPrice](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_3B3B.png)
#### Q3: What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
![3B3B2000sqft](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_3B3B2F_2000sqft.png)
#### Q4: What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? (Running time included)
![MoreThan350000](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_350000_view.png)
### Contrasting Running times
#### Normal Running Time
![MoreThan350000](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_350000_view.png)
#### Caching Data
![Caching](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_350000_view_cach.png)
#### Parqueting Data
![Parqueting Data](https://github.com/henrychan990805/Home_Sales/blob/bc4309c6661126ec71952d07a8a80d09f9e39df9/Screenshots/AvgPrice_350000_view_cach_p_p.png)
