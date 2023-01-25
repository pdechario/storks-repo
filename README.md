# storks-repo

## Group Members:
Andres Diazvictores <br/>
Ariel Rubinstein <br/>
Persephone Elizabeth Dechario <br/>
Sevval Deniz Erkurt <br/>
Valeria Wardini <br/>

## Stork Account Names and Passwords
Gmail; storkstorkyfiu@gmail.com; Helloworld11!!


## How To Create Database With PostgreSQL

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
