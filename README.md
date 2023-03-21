# column-database-family
HBbase is linearly scalable and it integrates with source and destination

HBase is most effectively used to store non-relational data, accessed via the HBase API. Apache Phoenix is commonly used as a SQL layer on top of HBase allowing you to use familiar SQL syntax to insert, delete, and query data stored in HBase.

HBase is a popular NoSQL database with high throughput and low latency. HBase is Java-based Not Only SQL i.e. NoSQL database which runs on top of Hadoop.

shop_details customer_details organic products

The shop_details stores inforamtion about 1)name 2)cost 3)item 4)location

The customer_details stores inforamtion about 1)name 2)age 3)mailid 4)location

The organic products stores information about 1)name 2)price 3)type 4)acidic

In this details table there are three columns named shop_details,cus_details,organic products

![Screenshot (88)](https://user-images.githubusercontent.com/124845766/226640914-1fdbb853-ffef-46a4-beed-25bc51e4e566.png)
updated the values of row 02 by changing their shop_detaild.And in the second row inserted the location info in the customer details.
finally deleted the last row of organic products that dropped using delete keyword
![Screenshot (89)](https://user-images.githubusercontent.com/124845766/226640977-de144545-58b2-4f34-b0d8-8a42b2ba6d99.png)
Each row had unique key and continue to generate and collect more data.

