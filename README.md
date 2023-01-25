# storks-repo
## how to create database with postgreSQL

CREATE USER username WITH PASSWORD 'password' CREATED; <br/>
CREATE DATABASE nodelogin; <br/>
\c nodelogin

CREATE TABLE users <br/>
(id BIGSERIAL PRIMARY KEY NOT NULL, <br/>
name VARCHAR(200) NOT NULL, <br/>
email VARCHAR(200) NOT NULL, <br/>
password VARCHAR(200) NOT NULL, <br/>
UNIQUE (email)); <br/>

SELECT * FROM users; --> to see your table
