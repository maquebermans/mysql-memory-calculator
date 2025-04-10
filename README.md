# Mysql Memory Calculator
Use this memory calculator to check MySQL memory allocation based on configuration settings used in your my.cnf file (or database flag for cloudsql).

## Pre-requisites
1. Make sure your instance can connect to the db :D
2. Store your db password in ~/.my.cnf
   ```bash
   [mysql]
    user=dbuser
    password=dbpassword
   ```
3. 

## Usage
1. Clone the repo
   ```bash
   git clone https://github.com/maquebermans/mysql-memory-calculator.git
   cd mysql-memory-calculator
   ```
2. Call the script
   ```bash
   ./cloudsql_mysql_memory_calc.sh <db_user> <db_ip> <db_port>
   ./cloudsql_mysql_memory_calc.sh dbuser 127.0.0.1 3306
   ```
   
