# Supermarket sales analysis
This project analyses sales data and extracts insights to optimize marketing campaigns.
The growth of supermarkets in most populated cities are increasing and market competitions are also high. 

## About the data set
* The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data.
* Predictive data analytics methods are easy to apply with this dataset.
* size of the dataset: 1000 x 13
## Metadata:

#1  <b>InvoiceID: Primary key of the dataset, uniquely identifies the invoice issued.<\b>
#2  
|Branch: Branch of supermarket in given city|
|---|
|'A':340|
|'B':332|
|'C':328|
 
#3 
|City: City which the customer roots from|
|---|
|'Yangon':340|
|'Naypyitaw':332|
|'Mandalay':328|

#4  
|Customer type: Membership status of the customer|
|---|
|'Member':501|
|'Normal':499|

#5  
|Gender: Gender of customer|
|---|
|'Female':501|
|'Male'  :499|

#6  
|Product line: The classification of product purchased by customer|
|---|
|'Health and beauty':152|
|'Electronic accessories':174|
|'Home and lifestyle':170|
|'Sports and travel':166|
|'Food and beverages':160|
|'Fashion accessories': 178|

#7  
|Payment: Method of payment chosen by the customer to pay for the commodities |
|---|
|Ewallet: 345|
|Cash: 344|
|Credit card: 311|

#8  
|Unit price: Price of each unit labelled by the supermarket in which the customer buys the product|
|---|
|mean: 55.67213|
|max: 99.96|
|min: 10.08|
|standard deviation: 26.494628|
|median: 55.23|


#9  
|Quantity: Number of units purchased by the customer of a given product|
|---|
|mean: 5.51|
|max: 10|
|min: 1|
|standard deviation: 2.923431|
|median: 5|

#10 
|cogs:	Total cost incurred by the supermarket for the goods purchased by the customer|
|---|
|mean: 307.58738|
|max:993|
|min: 10.17|
|standard deviation: 234.17651|
|median: 241.76|

#11 
|Rating: Degree of satisfaction of customer from the goods and services of the supermarket on a scale of 1-10|
|---|
|mean: 6.9727|
|max: 10|
|min: 4|
|standard deviation: 1.71858|
|median: 7|

#12 
|Date: Date on which the transaction took place and the invoice was printed|
|---|
|minimum: 2019-01-01|
|maximum: 2019-03-30|

#13 
|Time: Time on the given date on which transaction took place and invoice was printed|
|---|
|minimum: 10:00:00|
|maximum: 20:59:00|

#14 
|gross margin percentage: measures the profitability of a company's core business activities, percentage of revenuethat exceeds the cost of goods sold (COGS), also known as gross profit, relative to total revenue|
|---|
|mean: 4.761905|
|max: 4.761905|
|min: 4.761905|
|standard deviation: 0.00|
|median: 4.761905|

#15 
|gross income:  total earnings or revenue generated by an individual, organization, or entity before deducting any expenses or taxes|
|---|
|mean: 15.379369|
|max: 49.650000|
|min: 0.508500|
|standard deviation: 11.708825|
|median: 12.088000|

#16 
|Tax 5%: 5% part of profit that is counted as tax towards the government|
|---|
|mean: 15.379369|
|max: 49.65|
|min: 0.5085|
|standard deviation: 11.708825|
|median: 12.088000|

#17 
|Total: cogs + Tax 5% |
|---|
|mean: 322.966749|
|max: 1042.65|
|min: 10.6785|
|standard deviation: 245.885335|
|median: 253.848|

## Methodology
This project leveraged python and its vast libraries to extract insights from sales_data which is a versatile and popular programming language known for its readability and ease of use. It supports various programming paradigms and has a vast ecosystem of libraries and frameworks. 
Following libraries have been utilized for the purpose: 

![Screenshot 2024-04-16 220723](https://github.com/ISHOOO/Supermarket-sales-analysis/assets/132544766/1b3ec08a-4f04-4ca4-bb5c-230a0c36a586)

* Pandas:  a powerful library in Python used for data manipulation and analysis. It provides data structures like DataFrames and Series, which make it easy to work with structured data.

![Screenshot 2024-04-16 215105](https://github.com/ISHOOO/Supermarket-sales-analysis/assets/132544766/ac296d5c-4a09-4f78-b35a-beb00c7f91aa)

* Numpy:  a fundamental package for numerical computing in Python. It provides support for arrays, matrices, and mathematical functions, making it essential for scientific computing and data analysis tasks.

![Screenshot 2024-04-16 215218](https://github.com/ISHOOO/Supermarket-sales-analysis/assets/132544766/05501e4d-29f2-4545-a896-8cd75eeefbe8)

* Matplotlib: a widely-used Python library for creating static, interactive, and animated visualizations. It offers a wide range of plotting functions to visualize data in 2D and 3D formats.

![Screenshot 2024-04-16 215330](https://github.com/ISHOOO/Supermarket-sales-analysis/assets/132544766/e8412d3b-a6ea-472f-9ec2-75a4487db090)

* Seaborn: a statistical data visualization library based on Matplotlib. It provides a high-level interface for creating attractive and informative statistical graphics. Seaborn simplifies the process of creating complex visualizations by providing convenient functions and settings.

## Results
Following various types of insights were gained through the project:
* Customer Insights
* Membership insights
* Product insights
* Customer Satisfaction and loyalty
* Optimal marketing campaign timings
