$ npm install

------------------------------------------------

RUN this commands in your database:

# create database or add your database to .env file

create database if not exists library;

# create user or add your user ti .env file

CREATE USER 'userIryna'@'localhost' IDENTIFIED by 'test';
 
GRANT ALL on library.* to 'userIryna'@'localhost' ;
 
FLUSH PRIVILEGES;

-------------------------------------------------------

$ npm run build 
$ npm run start
