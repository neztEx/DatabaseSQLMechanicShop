# Mechanic Shop - SQL Database
A database application for a mechanics shop. The system will be used to track information about customers, cars, mechanics, car ownership, service request and billing information. The database is created using postgreSQL.

## Tools

Database: PostgreSQL

Language: Java


# Compilation Instructions

1. Setup server and table
    1. `cd code`
    2. `cd postgresql`
    3. `chmod +x *.sh`
    4. `./startPostgreSQL.sh`
    5. `./createPostgreDB.sh`
2. Run Java Script
    1. `cd code`
    2. `cd java`
    3. `chmod +x *.sh`
    4. `./compile.sh`
    5. `./run.sh $LOGNAME"_DB" 5432 $USER`
3. Exit Server
    1. `cd code`
    2. `cd postgresql`
    3. `./stopPostgreDB.sh`
`