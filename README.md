# World Cup Tournament Database

This project involves creating and managing a database to track World Cup tournament data, including game results, team information, and more. The database contains data from the final three rounds of World Cup tournaments since 2014.

## Project Structure

- **Database**: PostgreSQL database named `worldcup`.
- **Tables**:
  - `teams`: Stores information about each team.
  - `games`: Stores information about each game, including scores and participating teams.

## User Stories

1. **Create the Database**:
   - Create the `worldcup` database.
   - Define tables for `teams` and `games`.
   - Ensure proper foreign key relationships and constraints.

2. **Insert Data**:
   - Insert data from `games.csv` into the `games` and `teams` tables.
   - Use the `insert_data.sh` script for data insertion.

3. **Query the Database**:
   - Use the `queries.sh` script to generate reports and extract information from the database.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NicoPotrich/freeCodeCamp-Worldcup-Database.git
