# Back-end developer

The back-end job involves, but is not limited to, developing and maintaining
our cloud micro services written Java - that includes technologies
such as Rest APIs with Spring Cloud and MySQL as database. The job also needs critical
thinking in order to make the best and most scalable decisions.

## Requirements

- Java
- Git

## Coding test

To attend to this position the test below.

### 2 - Java

You need to create a **Rest API with Java version 1.8, Maven, Spring and MySql** to store a list of products from different suppliers to be used in our app. 

The supplier Entity must have this fields:

	* id
	* name
	* date of creation
	* date of the last update

You **don't need** to create endpoints to manage suppliers. Just create the table and insert at least 3 records to be used in products end points.

The product's fields are:

	* id
	* name
	* quantity in stock
	* unit price
	* supplier_id (reference to suppliers table)
	* date of creation
	* date of the last update

and the API must have a complete CRUD of products with the following resources:

	* An endpoint to list all product;
	* An endpoint to see just one product by 'id';
	* An endpoint to insert a new product;
	* An endpoint to update a product;
	* An endpoint to delete a product;
	- An endpoint to increase or decrease the quantity stock

You must delivery the database scritp, the API source code and a way to use this API, that could be a Postman Collection or a sequence of Curl commands.
And create a README.md file to explain how to install and use the API.

### Good luck

Now keep reading the README file to know how to return your results and
what should not be done.
