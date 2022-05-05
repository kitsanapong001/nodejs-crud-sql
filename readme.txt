https://expressjs.com/en/starter/generator.html

<-- CREATE DATABASE SQL -->

database name : nodejs_crud_db
CREATE TABLE books(
	id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name varchar(100) NOT NULL,
    author varchar(100) NOT NULL,
    created_at timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
    update_at timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
) ENGINE=INNODB DEFAULT CHARSET=utf8;