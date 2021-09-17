# Winter-2022-Data-Science-Intern-Challenge




Question 1: Given some sample data, write a program to answer the following: click here to access the required data set

On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis. 

a)Think about what could be going wrong with our calculation. Think about a better way to evaluate this data. 
b)What metric would you report for this dataset?
c)What is its value?


Question 2: For this question you’ll need to use SQL. Follow this link to access the data set required for the challenge. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.

a)How many orders were shipped by Speedy Express in total?


SELECT O.OrderID FROM [OrderDetails] OD\
INNER JOIN [Orders] O\
ON OD.OrderID = O.OrderID\
WHERE O.ShipperID = 1;

Number of order shipped by Speedy Express = 149


b)What is the last name of the employee with the most orders?
c)What product was ordered the most by customers in Germany?

