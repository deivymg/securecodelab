# Secure Code Lab
learn how to effectively secure a php web applications against the most common security issues



### Prerequisites.
1. Install a web server that supports PHP 7 or higher and a database. To facilitate this process, you can use a management system like XAMPP.

## Install Lab

2. Create a database user or use an existing one :

If your already have an account to connect to databse, you have to modify the Config.php file to match the pre-existing credentials in your database.

If you want to create a new user, execute the  database engine:

```sql
CREATE USER 'dbuser'@'localhost' IDENTIFIED BY 'dbpassword';
GRANT ALL PRIVILEGES ON databasename.* TO 'dbuser'@'localhost';

```
If you edit the username and password, remember to update the Config.php file to ensure it matches the new credentials.

3. 
