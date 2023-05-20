# E-Commerce Data Project #

### Data Explanation ###
----------
In this project, we play a role as a Data Analyst on E-commerce company. We have a database called **olist** to be explored to give our company the best insight into the business. The database consist of some tables and their relations is visualized as below :

![ER Diagram drawio](https://user-images.githubusercontent.com/91242818/230758495-248bce18-62bf-468c-8069-eca159417c9b.png)

Dataset: https://drive.google.com/file/d/1giqBhW11LO4Th0wXxsl_pVGABtknmg1_/view?usp=sharing

### Objectives ###
----------

With our database we want to answer several questions:
1. How is the number of orders trending each month?
2. How is the number of orders by time and day?
3. How is the delivery time trending each month?
4. Whether the number of orders each month affect the delivery time?
5. Whether the distance between the seller and the customer affect the delivery time?

### Data Process and Exploration ###
----------

Before jump to the question, we need to through some process, such as:

1. Data Cleaning
   * Handling missing values
   * Handling outliers
   * Handling inconsistent format
   * Handling duplicated data
2. Data Wrangling
   * Joining tables
3. Data Manipulation
   * Applying function
   * Pivoting data
   * Grouping data
4. Data Exploration
   * Visualizing data
5. ... and so on

All of this process have been done and written in **EDA on E-commerce Data.ipynb** file.

### Conclusions ###
----------
After doing all of those processes we get the answer of our questions:

1. In lately 2016, the number of orders is not much, but increased from 2017 to 2018. In the last month, the number of orders dropped dramatically because the data is not recorded in a full month. Despite that, it's a good sign to our business that order activity increase constantly.

![Figure 1](https://user-images.githubusercontent.com/91242818/230758502-929e7cc8-1ce8-4911-bdb8-b05a8fe7aca8.png)

2. Customers frequently order between 10 AM to 10 PM on weekdays. In that time interval, the number of orders is between 200 to 400 orders. Outside of that time, the order activity is a quite bit. In terms of business, we can do a midnight or weekend flash-sale program to increase order activity in that time period.

![Figure 2](https://user-images.githubusercontent.com/91242818/230758507-098302b0-834f-48cc-828e-7d18554e3688.png)

3. Even though the number of orders is increased, the delivery time tends to be consistent over months with the average between 6 and 8 days per order, in other word the number of orders doesn't impact the delivery time.

![Figure 3](https://user-images.githubusercontent.com/91242818/230758509-d7cd0019-ee67-4b69-a357-4132c1c75670.png)

4. The statement in number 3 can be proven by the coefficient correlation between number of orders and delivery time that is 0.14, which means those two variable have a negligible correlation.

![Figure 4](https://user-images.githubusercontent.com/91242818/230758511-f81392b8-8426-40c0-8f29-7a14ae131422.png)

5. Meanwhile, the delivery time is quite associated with the distance between seller and customer (not strong but moderate), can be seen at the coefficient correlation 0.46. The positive value in the coefficient correlation means the farther apart the seller and customer are, the longer the delivery will take.

![Figure 5](https://user-images.githubusercontent.com/91242818/230758513-31cf1e40-f548-4007-acd9-80e934150d06.png)

