# ARCHwk9
# Java Spring Boot Docker App Setup

## Overview
The Spring Boot Java application was deployed using Docker. The application used a vulnerable version of log4j and was exploited, and mitigated using several techniques.

## Prerequisites
Before running the application, ensure the following is installed:
1. Docker
2. Docker compose
3. Maven (could also edit Dockerfile to include the install)

## Setup Instructions
1.	Prepare the necessary files:
a.	Dockerfile
b.	Docker-compose
c.	Pom.xml
d.	src/main/java/com/example/LogController.java
e.	src/main/java/com/example/Application.java, need to define Spring Boot main class

2.	Build the Application
a.	Install Maven or edit Dockerfile to include the install
b.	Build the application using ‘docker compose up –build’

