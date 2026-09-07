<div align="center">
  <h1>Hi, I'm Madhur Patari</h1>
  <p>Software Engineer | Java Backend Developer | Spring Boot | Microservices</p>
</div>

## About Me

I'm a Software Engineer with a background in Mechanical Engineering who transitioned into software development because of my interest in programming and building real-world applications.

Over the past few years, I've worked across Java backend development, legacy Java applications, automation testing, Android utilities, telematics systems, and cloud-based data processing.

My primary focus is backend engineering. I work mainly with Java, Spring Boot, REST APIs, MySQL, and related backend technologies, and I'm currently strengthening my understanding of Microservices, System Design, distributed systems, and production-grade application development.

I enjoy understanding how systems work internally, designing clean backend architectures, and solving problems beyond just making the code work.

## Tech Stack

- **Languages:** Java, Python, SQL, JavaScript
- **Backend:** Spring Boot, Spring MVC, Servlets, REST APIs, JPA, Hibernate
- **Microservices:** Spring Cloud, API Gateway, Eureka Service Discovery
- **Security:** Spring Security, JWT
- **Database:** MySQL
- **Messaging & Data Processing:** Kafka, Apache Flink
- **Frontend:** React, HTML, CSS, JavaScript
- **Android:** Kotlin, BLE
- **Tools:** Git, GitLab, Maven, IntelliJ IDEA, Postman, Swagger
- **Currently Exploring:** Docker, Distributed Systems, System Design

## Experience

### Software Engineer — Trak N Tell

Worked across multiple software and telematics projects involving:

- Java and Servlet-based enterprise applications
- Migration of legacy Java components toward Spring-based architecture
- Backend development and REST APIs
- Python automation for telematics control unit testing
- Android BLE utility development
- Kafka-based data consumption
- Apache Flink applications for processing trip and charging data
- Integration and debugging across cloud, backend, mobile, and embedded systems

My current focus is on growing deeper into Java Backend Engineering, Microservices, and scalable application design.

## Featured Projects

### Satika — Microservices-Based E-Commerce Platform

Satika is a full-stack e-commerce platform for an online saree brand, designed using a microservices architecture.

Unlike my earlier projects, the focus here is not only on implementing CRUD APIs, but on understanding how independently deployable services communicate, authenticate users, manage distributed workflows, and work together as a complete system.

The application is being designed with separate services for major business capabilities such as:

- Authentication and user management
- Product catalog and inventory
- Shopping cart
- Order management
- Payment processing
- Service discovery
- API routing and gateway management

The Catalog service also manages inventory for the current version of the application, keeping the architecture practical without unnecessarily splitting services.

### Architecture

```text
                    Client
                      |
                      v
                 API Gateway
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
   Auth Service   Catalog Service  Cart Service
                      |
                      |
        +-------------+-------------+
        |                           |
        v                           v
   Order Service              Payment Service
                                    |
                                    v
                                 Razorpay

              Eureka Service Discovery

        Each service owns its own database/schema
````

### Key Concepts Implemented / Being Implemented

* Microservices architecture
* Independent service deployment
* API Gateway
* Eureka Service Discovery
* JWT-based authentication
* Spring Security
* Service-to-service communication
* Separate database/schema per service
* Cart and order workflows
* Inventory management
* Payment integration using Razorpay
* REST API design
* Swagger / OpenAPI documentation
* Exception handling and validation

**Tech Stack:**

`Java` `Spring Boot` `Spring Cloud` `Spring Security` `JWT` `Eureka` `API Gateway` `MySQL` `React` `Vite` `Razorpay` `Maven` `Swagger`

This project is also helping me practically understand concepts such as service boundaries, distributed communication, failure handling, data ownership, and the trade-offs involved in microservices architecture.

---

### [FinTrack](https://github.com/Madhurpatari/FinTrack)

FinTrack is an Expense Tracker REST API built using Java and Spring Boot.

It allows users to manage and analyse their expenses through backend APIs.

Features include:

* Create, update, and delete expenses
* Retrieve expenses based on date and time
* Calculate weekly and monthly spending
* Generate expense summaries
* Maintain user-specific expense records

**Tech Stack:**

`Java` `Spring Boot` `REST API` `MySQL` `Maven`

## What I'm Currently Working On

My current learning and development focus is around backend engineering rather than collecting frameworks.

```text
Java
Spring Boot
Microservices
System Design
Distributed Systems
SQL
DSA
```

I'm particularly focusing on:

* Java internals
* Collections and concurrency
* Spring Boot internals
* Spring Security
* Microservices communication
* API Gateway and Service Discovery
* Database design
* System Design — HLD and LLD
* Distributed systems fundamentals
* Writing production-oriented backend code
* Data Structures and Algorithms

## Backend Engineering Journey

```text
Java
  |
  v
Spring Boot
  |
  v
REST APIs
  |
  v
Microservices
  |
  v
Distributed Systems
  |
  v
Scalable Backend Engineering
```

## Education

**DIT University, Dehradun**

B.Tech in Mechanical Engineering

My engineering background gave me a structured approach to problem-solving and analytical thinking, which eventually helped me transition into software engineering.

## Connect With Me

* **LinkedIn:** [Madhur Patari](https://www.linkedin.com/in/madhur-patari-996620366/)
* **LeetCode:** [kmadhur07](https://leetcode.com/kmadhur07/)
* **HackerRank:** [kmadhur07](https://www.hackerrank.com/kmadhur07?hr_r=1)

## Beyond Code

Outside software development, I enjoy mountains, trekking, and photography.

I believe in understanding fundamentals, building things practically, and continuously improving as an engineer.

---

<div align="center">
  <b>Keep learning. Keep building.</b>
</div>
```

This version tells a much better story: **professional experience → serious microservices project → backend specialization**. Satika becomes the project a recruiter should notice first, while FinTrack shows your earlier Spring Boot foundation.
