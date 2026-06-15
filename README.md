<<<<<<< HEAD
# Dockerized Three-Tier Application

## Project Overview

This project demonstrates a Dockerized Three-Tier Architecture deployed on AWS EC2 using Docker containers.

### Architecture

Frontend (Nginx Container)

↓

Backend (Spring Boot Container)

↓

MySQL Database Container

## Technologies Used

* AWS EC2 (Amazon Linux 2023)
* Docker
* Nginx
* Java 21
* Spring Boot
* MySQL 8
* Git
* GitHub

## Project Structure

dockerized-three-tier-application/

├── frontend/

│   ├── Dockerfile

│   └── index.html

├── backend/

│   ├── Dockerfile

│   └── app.jar

└── README.md

## Frontend Tier

The frontend is built using HTML and served through an Nginx container.

Features:

* Static web page
* Nginx web server
* Dockerized deployment

## Backend Tier

The backend is developed using Spring Boot and Java 21.

Features:

* REST API
* Spring Boot Framework
* Dockerized deployment
* Runs on Port 8080

## Database Tier

The database layer uses MySQL 8 running inside a Docker container.

Features:

* Relational Database
* Persistent Storage
* Containerized Deployment

## Docker Commands

Build Frontend Image

docker build -t frontend:v1 .

Run Frontend Container

docker run -d --name frontend-container -p 80:80 frontend:v1

Build Backend Image

docker build -t backend:v1 .

Run Backend Container

docker run -d --name backend-container -p 8081:8080 backend:v1

Run MySQL Container

docker run -d --name mysql-container -e MYSQL_ROOT_PASSWORD=root123 -e MYSQL_DATABASE=appdb -p 3306:3306 mysql:8

## AWS Deployment

Region: ap-south-1

Platform: Amazon Linux 2023

## Learning Outcomes

* Docker Image Creation
* Container Management
* Multi-Tier Architecture
* Spring Boot Deployment
* Nginx Configuration
* MySQL Containerization
* AWS EC2 Deployment

## Author

Vignesh

AWS | Linux | DevOps | CCNA

=======
# dockerized-three-tier-application
>>>>>>> 78b645b9b2a85fc5c0a24045091259cabb32c48d
