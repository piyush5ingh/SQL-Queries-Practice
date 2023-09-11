##  Project: Car Rentals with SQL

**Overview:**

Welcome to my MySQL Project. This project showcases a collection of SQL queries along with detailed instructions and explanations.

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
2. **Rent a Car**
3. **Update Drop-Off Location and Extend Rental**
4. **Fetch Rental Details**
5. **Fetch Vehicle Details**
6. **Customer with Most Rental Insurances**

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

