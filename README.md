## Storks Web App
We are developing a web application for FIU Students, intended to be used for helping each other with day-to-day student struggles. The purpose of the service is to get the FIU Student community to cooperate with each other, by providing a space where students can request help that is filtered into categories and provide support to fellow students who will be rewarded with “Stork Points.” Stork Points can be redeemed on the app for purchases in campus locations, such as Starbucks coffee or Half Moon Empanadas.

## What is the background of the project idea? What is the problem?
The background of this project idea consists of helping FIU students with problematic tasks such as help with homework. There is no specific problem that we are solving but rather we are creating an app that helps students with things like homework and brings the community together. It is designed to allow students to request help from their peers on things like specific assignments or coursework. Students can choose to accept these requests and offer assistance or ask for assistance themselves. Through participating in activities like “peer-to-peer homework help”, students can earn points that can be redeemed for rewards or incentives through Florida International University. </br>


## Group Members:
Andres Diazvictores <br/>
Ariel Rubinstein <br/>
Persephone Elizabeth Dechario <br/>
Sevval Deniz Erkurt <br/>
Valeria Wardini <br/>

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
