# SQL-Queries-Practice
MySQL database querying skills through a variety of MySQL queries

**README:**

Welcome to my MySQL Query Practice Repository. This project showcases a collection of SQL queries along with detailed instructions and explanations. Whether you're a beginner or an experienced data enthusiast, you'll find valuable examples and guidance to help you master database querying.

##  Getting Started

To run these queries and explore the instructions, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.

2. **Database Setup**: Import the provided `lco_car_rentals.sql` file into your MySQL database. You can use the following command to import the database:

   ```bash
   mysql -u username -p database_name < lco_car_rentals.sql
   ```


3. **Running Queries**: Navigate to the relevant query files in the repository and follow the provided instructions to run the queries.

## Queries Included

1. **Insert New Customer**
   - Description: Insert details of a new customer.
   - SQL File: [insert_customer.sql](/queries/insert_customer.sql)

2. **Rent a Car**
   - Description: Rent a car with specified details.
   - SQL File: [rent_car.sql](/queries/rent_car.sql)

3. **Update Drop-Off Location and Extend Rental**
   - Description: Update drop-off location and extend rental duration.
   - SQL File: [update_dropoff_extend_rental.sql](/queries/update_dropoff_extend_rental.sql)

4. **Fetch Rental Details**
   - Description: Fetch rental details including equipment type.
   - SQL File: [fetch_rental_details.sql](/queries/fetch_rental_details.sql)

5. **Fetch Vehicle Details**
   - Description: Fetch details of available vehicles.
   - SQL File: [fetch_vehicle_details.sql](/queries/fetch_vehicle_details.sql)

6. **Customer with Most Rental Insurances**
   - Description: Get the customer with the most rental insurances.
   - SQL File: [customer_with_most_insurances.sql](/queries/customer_with_most_insurances.sql)

## Formulas

Here are some SQL formulas used in the queries:

- **Insert Data**: `INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);`

- **Update Data**: `UPDATE table_name SET column1 = value1, column2 = value2, ... WHERE condition;`

- **Select Data**: `SELECT column1, column2, ... FROM table_name WHERE condition;`

- **Join Tables**: `SELECT ... FROM table1 INNER JOIN table2 ON table1.column = table2.column;`

- **Calculate Dates**: To add or subtract days from a date, use the `DATE_ADD` and `DATE_SUB` functions.

  ```sql
  SELECT DATE_ADD(start_date, INTERVAL 4 DAY) AS extended_date FROM rental;
  ```

## Contributors

- [Your Name](https://github.com/Piyush5ingh) 

- 
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
```
