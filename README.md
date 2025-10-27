# Introduction
VProfile is a multi-tier web application designed to demonstrate a complete DevOps lifecycle — from code commit to deployment.  
This project implements Continuous Integration, Continuous Delivery, Infrastructure as Code, and Monitoring using modern DevOps tools.

---
## 🏗️ Project Architecture

### Application Components
The VProfile app consists of five main services:

| Component | Technology | Description |
|------------|-------------|--------------|
| **Nginx** | Web Server / Load Balancer | Routes traffic to the backend application servers |
| **Tomcat** | Application Server | Hosts the Java-based web application (WAR) |
| **RabbitMQ** | Message Broker | Handles asynchronous communication between services |
| **Memcached** | Caching Server | Speeds up dynamic database-driven websites |
| **MySQL** | Database | Stores persistent data for the application |

### Infrastructure Overview
The architecture follows a **3-tier design**:

# Architecture Overview
# Tech Stack
# Deployment Workflow
# CI/CD Pipeline
# Infrastructure Diagram
# Steps to Run (Manual + Automated)






















# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


