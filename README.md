# Gangster-Legends-V2

Gangster Legends v2 is a open source PBBG game engine written in PHP using a MySQL backend.

# Requirements

- PHP 5.6.X or higher
- MySQL 5.5 or higher

# How To Install

1. Extract files to your webserver
2. Create a new database and a user
3. Import first`install/schema.sql` and then `install/data.sql` to your MySQL Database
4. Open up `dbconn.php` and alter the connection string with your MySQL username, password and database name
exp/    ("mysql:host=localhost;dbname= db naam", "user naam", "wachtwoord")
5. The game should now be made with some sample data
6. You can login with the email `Admin@yourgame.com` and the password `adminPass`
7. Go to your profile and change your password

# Example

A demo can be found at http://glscript.cdcoding.com/demo/

The email is `Admin@yourgame.com` and the password is `adminPass` 
