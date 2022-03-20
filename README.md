# -CRUD-Operations

#Database queries

* CREATE DATABASE demo;
* use demo;
* CREATE TABLE `users` (
`id` INT(11) NOT NULL AUTO_INCREMENT,
`name` VARCHAR(255) NULL DEFAULT NULL,
`age` VARCHAR(255) NULL DEFAULT NULL,
`email` VARCHAR(255) NULL DEFAULT NULL,
`created` DATETIME NULL DEFAULT NULL,
PRIMARY KEY (`id`)
)
COLLATE='latin1_swedish_ci'
ENGINE=InnoDB
AUTO_INCREMENT=1;


- then add insert query
