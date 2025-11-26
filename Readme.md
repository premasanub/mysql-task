   
# MySQL Task — GUVI Task 1

A small collection of MySQL practice tasks (queries, schema, and example data) created for learning and evaluation.

## What's in this repository
- SQL files containing schema, sample data, and solutions.
- A README describing how to set up and run the tasks.

## Prerequisites
- MySQL server (recommended: 8.x)
- MySQL client (mysql CLI or a GUI such as MySQL Workbench)
- Basic knowledge of SQL (SELECT, JOIN, GROUP BY, subqueries)

## Setup (quick)
1. Start the MySQL server.
2. Open a terminal or MySQL client.
3. Create a database and import provided SQL:
    - Using mysql CLI:
      - mysql -u <user> -p
      - CREATE DATABASE guvi_tasks;
      - USE guvi_tasks;
      - SOURCE path/to/schema.sql;
      - SOURCE path/to/sample_data.sql;

4. Run queries from the task files or execute the example solution files:
    - mysql -u <user> -p guvi_tasks < solutions/task1_solution.sql

## Example tables (for reference)
- customers (id, name, email, created_at)
- products (id, name, category, price)
- orders (id, customer_id, order_date, total)
- order_items (id, order_id, product_id, quantity, price)

## Common tasks
- Aggregate (SUM, AVG, COUNT)
- Joins (INNER, LEFT, CROSS)
- Window functions (ROW_NUMBER, RANK)
- Subqueries (correlated and uncorrelated)
- Grouping and filtering (GROUP BY, HAVING)
- Data modification (INSERT, UPDATE, DELETE)

## How to test your solutions
- Compare outputs of your queries against provided solution queries.
- Use small data sets from sample_data.sql to verify edge cases.

## File structure (suggested)
- README.md
- schema.sql            — table definitions
- sample_data.sql       — seed/sample rows
- tasks/                — problem statements (.md)
- solutions/            — solution SQL files

## Contributing
- Add new tasks and solutions as separate files under tasks/ and solutions/.
- Keep SQL deterministic and include sample data when necessary.

## License
Keep or add a license appropriate for your use (e.g., MIT).

If you want, I can create example schema.sql, sample_data.sql, or specific task files next.
    