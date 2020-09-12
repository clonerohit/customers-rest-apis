# customers-rest-apis-impl
Implementation of Customer's REST APIs

This project is the implementation of REST APIs on Customer Entity using Form.

Here the the endpoints of APIs:

1. GET : http://localhost:8080/customers
2. POST : http://localhost:8080/customers
3. PUT : http://localhost:8080/customers/{customer_id}
4. DELETE : http://localhost:8080/customers/{customer_id}

Technologies Used in the Project:

1. Spring/Spring Boot
2. MySQL
3. Maven
4. JSP/HTML
5. JavaScript
6. JQuery/AJAX

To run the project, create a schema first with the below script:

create database 'customers';

Note: Make sure that you change the values of DB configs in application.properties

To run:

mvn eclipse:eclipse && mvn clean install

mvn spring-boot:run

The project is contributed by Rohit Suthar on Sept 12th 2020.

