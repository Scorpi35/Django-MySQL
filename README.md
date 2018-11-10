# Installing and configuring MySQL for Django

###### Steps
-> Install MySQL
-> Create MySQL Database
-> Install MySQL Django adapter, mysqlclient
-> Configure Settings.py

###### Creating user in mysql

  -> CREATE USER 'username@localhost' IDENTIFIED BY 'Your_Password';

###### Granting privileges to the user

  -> CREATE DATABASE database;
  -> GRANT ALL PRIVILEGES ON database.* TO 'username'@'localhost';
  -> FLUSH PRIVILEGES;
  -> QUIT

###### On Terminal

  -> python manage.py makemigrations
  -> python manage.py migrate
