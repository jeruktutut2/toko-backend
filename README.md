create database
:
CREATE DATABASE IF NOT EXISTS toko;

create table user:
CREATE TABLE user (  
	id varchar(36) NOT NULL,  
	name varchar(255) DEFAULT NULL,  
	username varchar(255) NOT NULL,  
	password varchar(255) NOT NULL,  
	created_by varchar(36) DEFAULT NULL,  
	created_date datetime DEFAULT NULL,  
	updated_by varchar(36) DEFAULT NULL,  
	updated_date datetime DEFAULT NULL,  
	PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1