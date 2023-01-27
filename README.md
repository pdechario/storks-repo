# storks-repo
This repo 

## Group Members:
Andres Diazvictores <br/>
Ariel Rubinstein <br/>
Persephone Elizabeth Dechario <br/>
Sevval Deniz Erkurt <br/>
Valeria Wardini <br/>

## Stork Account Names and Passwords
Gmail; storkstorkyfiu@gmail.com; Helloworld11!!


## How To Create Database With PostgreSQL

CREATE USER username WITH PASSWORD 'password' CREATEDB; <br/>
\q <br/>
relogin with your new user <br/>

CREATE DATABASE nodelogin; <br/>
\c nodelogin

CREATE TABLE users <br/>
(id BIGSERIAL PRIMARY KEY NOT NULL, <br/>
name VARCHAR(200) NOT NULL, <br/>
email VARCHAR(200) NOT NULL, <br/>
password VARCHAR(200) NOT NULL, <br/>
UNIQUE (email)); <br/>
INSERT INTO users (name, email, password) <br/>
VALUES ('Andres', 'adiaz@gmail.com', 'password'); <br/>

SELECT * FROM users; --> to see your table
