# Java Web Application – DevOps Multi-VM Project (Vagrant)

## 📌 Project Overview

This repository contains a **Java-based web application** developed and deployed as part of the **DevOps course by Imran Teli**.

The main purpose of this project is to **learn and practice DevOps concepts** by setting up a **multi-VM environment** using **Vagrant**, where each service runs on a **separate CentOS 9 virtual machine**.  
The project simulates a **real-world production-like infrastructure** for hosting a Java web application.

---

## 🎯 Learning Objectives

Through this project, I gained hands-on experience with:

- Vagrant and multi-VM provisioning
- Setting up services on separate virtual machines
- Infrastructure segregation and service communication
- Hosting a Java web application using Tomcat
- Using Nginx as a reverse proxy
- Integrating MySQL, RabbitMQ, and Memcached
- Working with enterprise-level DevOps tooling

---

## 🧱 Architecture

The application is deployed using multiple **CentOS 9** virtual machines:

| Service | Description |
|-------|------------|
| Nginx | Reverse proxy |
| Tomcat | Java application server |
| MySQL | Relational database |
| Memcached | Caching layer |
| RabbitMQ | Message broker |
| ElasticSearch | Search engine |
| App VM | Spring MVC application |

Each service runs on its **own VM** to closely resemble real-world distributed systems.

---

## 🛠️ Tech Stack

### Application & Frameworks
- Java (JDK 17 / 21)
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP

### Servers & Infrastructure
- Apache Tomcat
- Nginx
- Vagrant
- CentOS 9

### Databases & Messaging
- MySQL 8
- RabbitMQ
- Memcached
- ElasticSearch

---

## ✅ Prerequisites

Ensure the following are installed on your system:

- JDK 17 or 21  
- Maven 3.9  
- MySQL 8  
- Vagrant  
- VirtualBox or VMware  

---

## 🗄️ Database Setup

This project uses **MySQL** as the database.

### Database Dump File

The SQL dump file is located at:

