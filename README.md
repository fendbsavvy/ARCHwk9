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
Prepare the necessary files:
  1. Dockerfile
  2. Docker-compose
  3. Pom.xml
  4. src/main/java/com/example/LogController.java
  5. src/main/java/com/example/Application.java, needed to define Spring Boot main class

Build the Application
 1. Build the application using ‘docker compose up –build’

