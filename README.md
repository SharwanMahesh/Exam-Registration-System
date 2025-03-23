# Exam-Registration-System
Exam Registration System for OOAD

MySQL- SQL code

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100),
    subject VARCHAR(100),
    username VARCHAR(50) UNIQUE,
    password VARCHAR(100)
);
