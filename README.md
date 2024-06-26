**Sales Data Analysis**

The main objective of the project is to analyze the provided sample sales dataset to understand the sales performance, identify patterns, and extract valuable insights to make data-driven decisions  and provide response to the following business questions.

1.  What is the overall trend of sales over time?
2.  Which products have the highest sales?
3.  What is the correlation between sales and dealsize?
4.  How do different regions perform in terms of sales and dealsize?
5.  Which products contribute the most to the total sales?

The dataset was imported from Excel using pandas python library, then performed exploratory data analysis on the dataset to identify irregular data, missing values. After that, fixed the missing values by replacing the missing values with the mode. The dataset has 2823 data points with 25 columns.

The analysis performed to address the business requirement  includes;

1.  Analyse the sales data by grouping and aggregating the data based on different factors, such as product, region, or date.
2.  Calculate the percentage of sales contributed by each region. 
3.  Analyse the performance of different products in terms of sales. 
4.  Calculate the correlation between sales and dealsize.
5.  Identify the top-performing (top 3) products in terms of sales year on year.
6.  Calculate the percentage of sales contributed by the top-performing products.
7.  Analyse the performance of different regions in terms of sales and dealsize.   

The key insights observed in the dataset are.

1.  The overall sales trend reveals a seasonal steady increase in sale from September to November, and significant fall in December.
2.  Overall, classic cars have the highest sales with a value of 3,919,615.66, follow by vintage cars with a value of 1,903,150.84, then motocycles with a value of 1,166,388.34.
3.  It was observed that there is positive correlation overall, the large dealsize performed better than the medium dealsize, while the medium also performed better than the small dealsize in terms of sales.
4.  EMEA region is the best performing region, with medium dealsize value of 5,364,111.24, follow by the small dealsize with 2,293,672.67 in value of sales, then large dealsize with 1,173,549.89 sale value. Also, APAC region is next, with medium dealsize value of 723,321.00, follow by the small dealsize with 349,404.68 in value of sales, then large dealsize with 128,569.37 sale value.
5.  The products that contributed most to total sales are classic cars, vintage cars and motorcycles

**Conclusion and recommendation**

I will recommend the enhancement of the data collection process, to ensure that important data that could be of great value for future analysis should not be omitted, and data are validated for quality before keeping on rest. Because, missing was observed in the dataset which are important to the analysis, though this was handled by imputation.

Also, a further investgation may be require to study the cause and impact of the seasionality observed in the sales of some products, like Ship,Vintage Cars,Planes and classic cars, from Jan 2003 till August 2003. And also, a sudden drop in sales for almost all the products Decembers.

Lastly, an end year sales promotion initiative can be considered for implementation to improve sales in Decembers and reduce the effect of whatever factor that causes the sudden sales drop.
