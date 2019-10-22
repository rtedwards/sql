# sql
Learning SQL



# MySQL commands

## Create User and Grant Permissions
CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON  bank . * TO 'user'@'localhost';

## Login with username and database
mysql -u username -p database

## MySQL server allows check constraints to be defined but does not enforce them.
gender CHAR(1) CHECK (gender IN ('M','F'))  # Does not enforce
gender ENUM('M','F') # Does enforce

