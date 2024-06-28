## RUN in terminal

$ npm install

------------------------------------------------

## RUN this commands in your database:

## create database or add your database to .env file

$ CREATE DATABASE if not exists library;

## create user or add your user to .env file

$ CREATE USER 'userIryna'@'localhost' IDENTIFIED by 'test';
 
$ GRANT ALL on library.* to 'userIryna'@'localhost' ;
 
$ FLUSH PRIVILEGES;

-------------------------------------------------------

## RUN in terminal

$ npm run build 
$ npm run start
