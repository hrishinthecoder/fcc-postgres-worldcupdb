# WorldCup Database Project

This project involves creating a WorldCup database using PostgreSQL and utilizing bash scripts to insert data into the database and query the data.

## Database Setup

1. Install PostgreSQL: Make sure you have PostgreSQL installed on your system.
2. Create Database: Use the commands in `worldcup.sql` to create the WorldCup database

## Inserting Data

1. Data Preparation: Prepare the data files containing information about WorldCup matches, teams.
2. Bash Script: Use the bash script `insert_data.sh` to insert data into the WorldCup database. 

## Querying Data

1. Bash Script: Utilize the bash script `query.sh` to run SQL queries on the WorldCup database.
2. Match the results of the queries in the `expected_output.txt` file.

## Files in the Repository

- `worldcup.sql`: SQL script to create the database schema.
- `insert_data.sh`: Bash script to insert data into the database.
- `query.sh`: Bash script to query the database.
- `expected_output.txt`: Contains the output of the queries.
- `games.csv`: Include the data used for inserting into the database.

## Usage

1. Execute the database setup steps mentioned above.
2. Run the `insert_data.sh` script to populate the database.
3. Use the `query.sh` script to retrieve and analyze data.
4. Refer to `expected_output.txt` for result.

## Dependencies

- PostgreSQL
- Bash

## References

- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Bash Guide](https://www.gnu.org/software/bash/)
