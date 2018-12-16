create database: 
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
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

INSERT INTO user VALUES 
('4a4f9360-0113-11e9-8eb2-f2801f1b9fd1','admin1','admin1','$2a$10$d9zAWQ827RNJarHvKDjUju9SSl6Iv7OYYc1UhZOFWmH8QzsUWvjiu','',NOW(),NULL,NULL),
('4a4f95f4-0113-11e9-8eb2-f2801f1b9fd1','admin2','admin2','$2a$10$d9zAWQ827RNJarHvKDjUju9SSl6Iv7OYYc1UhZOFWmH8QzsUWvjiu','',NOW(),NULL,NULL),
('4a4f975c-0113-11e9-8eb2-f2801f1b9fd1','admin3','admin3','$2a$10$d9zAWQ827RNJarHvKDjUju9SSl6Iv7OYYc1UhZOFWmH8QzsUWvjiu','',NOW(),NULL,NULL);
