Создание БД через MySQL

mysql -u root -p

CREATE DATABASE test4;

USE test4;

CREATE TABLE customer(
firstName VARCHAR(30) NOT NULL,
lastName VARCHAR(30) NOT NULL,
custID INT UNSIGNED NOT NULL PRIMARY KEY);
