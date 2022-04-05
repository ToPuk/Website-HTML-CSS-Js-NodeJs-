# website
Bie daalt

# create database
```javascript
CREATE DATABASE `nodelogin`;
```
# create table 
```javascript
CREATE TABLE `accounts` (
  `id` int NOT NULL AUTO_INCREMENT,
  `username` varchar(50) NOT NULL,
  `password` varchar(255) NOT NULL,
  `email` varchar(100) NOT NULL,
  `profilePicture` varchar(255) DEFAULT NULL,
  `column_6` tinyint(1) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=31 DEFAULT CHARSET=utf8;
```
# insert user
```javascript
INSERT INTO `nodelogin`.`accounts` (`username`, `password`, `email`) VALUES ('test', 'test', 'test@test.com');
```
# install modules
```javascript
$ npm i
```
or
```javascript
$ npm install
```
# run server
```javascript
$ npm start
```
# view website
```javascript
localhost:3000
```
or
```javascript
127.0.0.1:3000
```
