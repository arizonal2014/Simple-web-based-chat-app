# Simple-web-based-chat-app
This simple web based application will allow multiple users to concurrently chat with each other from their browsers.

create a table in MySQL using the following SQL CREATE queries to create a database called chat and a table in that database called chatlog:
Click here to view code image

CREATE DATABASE chat;
USE chat;
CREATE TABLE chatlog (
     id INT(11) AUTO_INCREMENT PRIMARY KEY,
     message TEXT,
     sent_by VARCHAR(50),
     date_created INT(11)
);
