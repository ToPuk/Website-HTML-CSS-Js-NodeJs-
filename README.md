# website
Bie daalt

# create database
CREATE DATABASE `nodelogin` /*!40100 DEFAULT CHARACTER SET utf8 */ /*!80016 DEFAULT ENCRYPTION='N' */;

# create table 
CREATE TABLE `accounts` (
  `id` int NOT NULL AUTO_INCREMENT,
  `username` varchar(50) NOT NULL,
  `password` varchar(255) NOT NULL,
  `email` varchar(100) NOT NULL,
  `profilePicture` varchar(255) DEFAULT NULL,
  `column_6` tinyint(1) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=31 DEFAULT CHARSET=utf8;

# insert user
INSERT INTO `nodelogin`.`accounts` (`username`, `password`, `email`) VALUES ('test', 'test', 'test@test.com');
