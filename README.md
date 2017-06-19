# Simple-web-based-chat-app
This simple web based chat application will allow multiple users to concurrently chat with each other from their browsers.

# Using jQuery and AJAX with PHP
This application will allow multiple users chat with each other from their browsers, and receive these messages without having to refresh the browser window at all.

<img src="https://github.com/arizonal2014/Simple-web-based-chat-app/blob/master/vw50nfC6Xs.gif">


#  Create a table in MySQL 
using the following SQL CREATE queries to create a database called chat and a table in that database called chatlog:

<pre>
CREATE DATABASE chat;
USE chat;
CREATE TABLE chatlog (
     id INT(11) AUTO_INCREMENT PRIMARY KEY,
     message TEXT,
     sent_by VARCHAR(50),
     date_created INT(11)
);
</pre>
