# Getting Started with Spring - Workshop

Learn the fundamentals of Spring, build and deploy your first application.

## Run Keeper Application

The application you will build during this workshop revolves around the domain of tracking physical fitness. In the first
iteration of it we will use it track indoor and outdoor runs. 

org.codemash.runkeeper

- id,
- startedOn(LocalDateTime),
- completedOn(LocalDateTime),
- distance,
- time,
- type(indoor/outdoor),
- shoe(brand/name/color),
- avg_pace(calculated),
- title(Monday Morning Run)

## Objectives and Outcomes

- Learn how to create a basic Spring Boot application.
- Learn a few of the fundamentals of Spring
- Build a CRUD REST API
- Connect to a database
- Deploy a Spring Boot application into production

## Prerequsites

- Beginner / Intermediate Java experience
- Experience with Java Build Tools (Maven or Gradle)
- Software
    - Java 17 JDK
    - IDE or Text Editor for Java Develoopment
        - IntelliJ IDEA Ultimate 2022.3
            - This is what we are using (30 day trail)
            - Community Edition (Has some limitations)
        - Visual Studio Code
        - Spring Tool Suite

## Agenda

- Introduction (30 min)
    - Who are we
    - Spring Office Hours
    - Agenda
        - Workshop Agenda / Sections
        - Prerequisites
            - java -version
            - macOS/Windows/Linux
                - DaShaun show Windows / Linux setup
    - What is Spring?
        - What types of applications can you build with Spring? (Motivation for the workshop)
        - Spring Framework vs Spring Boot
        - Spring.io walkthrough
            - Reference Documentation
            - API Documentation
            - Spring Project Ecosystem
        - Tanzu Developer Center
    - Spring Boot Features
        - Spring Boot Starters (Dependency Management)
        - Auto Configuration
        - Simplified Deployment
    - What are we going to build?
        - Github Repository
        - Source Code + Slides Repo
        - Provide a list of resources (cover this)
- Getting Started (15 min)
    - start.spring.io
    - Examine pom.xml
        - Spring Boot Starters
        - Dependency Versions
    - Main Application Class
        - @SpringBootApplication annotation
    - How to start the application
        - IDE
        - Maven
        - View the application / browser & command-line
- Core Fundamentals & Features (1hr)
    - Structuring your code
        - Main Application in root package above other classes
        - Architecture (Layered/Hexagonal)
    - Spring Beans
        - @Component / @Controller / @RestController / @Service / @Repository
        - @Bean
    - Application Context
    - Dependency Injection & IoC
    - Configuration
        - Externalized Configuration (Property Sources)
        - application.properties / application.yml
    - Profiles
    - Logging
    - DevTools
- Spring Web (MVC) (1 hr)
    - Model View Controller (MVC)
    - Static index.html support
    - Building REST APIs
        - Annotations
        - CRUD REST API
        - API testing (curl/httpie/postman)
        - CORS
    - Error Handling
    - Data Validation
- Data (1 hr)
- What is Spring Data?
    - Spring Data Modules
    - JPA vs JDBC
- Configuring a datasource
    - H2 In-Memory DB
    - PostgreSQL
    - Logging / Debugging
- Spring Data JDBC
- Spring Data Repositories
- DDL Script
- Populate Database (CommandLineRunner)
- Spring to Production (15 min)
    - Jar
    - Containers
    - Native Images using GraalVM
        - Environment Variables
    - Single Page deployment instructions
