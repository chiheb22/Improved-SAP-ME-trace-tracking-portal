
# README

## Project Overview

### Project Title: **Amélioration du Portail du Suivi de Traces SAP ME**

### Author: **Chiheb KHEMIRI**

### Host Company: **Sagemcom Tunisie**

---

## Table of Contents

1. [Introduction](#introduction)
2. [Company Overview](#company-overview)
3. [Project Objectives](#project-objectives)
4. [Needs Analysis](#needs-analysis)
5. [Conceptual Study](#conceptual-study)
6. [Implementation](#implementation)
7. [Application Presentation](#application-presentation)
8. [Conclusion](#conclusion)
9. [References](#references)

---

## Introduction

This project was undertaken as part of a mandatory summer internship to improve the SAP ME traceability portal for Sagemcom Tunisie. The primary aim was to develop an application for tracking product passages and facilitating data consultation and parameterization.

---

## Company Overview

Sagemcom is a French industrial group specializing in broadband, audio-video solutions, and energy management (electricity, gas, and water). With over 6,500 employees in more than 50 countries, Sagemcom designs, manufactures, and ships over 40 million terminals annually.

---

## Project Objectives

The main goals of this project were:

1. **Business Need Identification**: To aid in project realization.
2. **Platform Design**: Creating a user-friendly interface.
3. **Mastering Tools and Frameworks**: Including Angular, Spring Boot, PostgreSQL, IntelliJ, and Postman.
4. **Project Implementation**: Developing a functional application.

The application allows users to:
- View traces provided by the system's sensors based on various criteria (creation date, update date, operation, serial number).
- Automatically send daily emails to users with trace details.
- Authenticate using LDAP technology.

---

## Needs Analysis

### Functional Requirements

1. **User Management**: Handling access for users already in the database.
2. **Data Management**: Consolidating data for visualization.
3. **Automated Emailing**: Sending daily emails to users.

### Non-Functional Requirements

1. **Error Management**: Clear error messages to guide users.
2. **Ergonomics**: A user-friendly, intuitive interface.
3. **Security**: Protecting user data and access permissions.
4. **Reliability**: Ensuring a bug-free, consistent platform.
5. **Maintainability**: Standard, clear architecture for easy maintenance.

---

## Conceptual Study

### Architecture

The application follows a three-tier architecture:
1. **Presentation Layer**
2. **Business Logic Layer**
3. **Data Access Layer**

### Behavioral View

- **UML Diagrams**: Used for visualizing system design.
Use case diagram
![Login Interface](images/use%20case%20diagram%20.jpeg)

class diagram
![Login Interface](images/class%20diagram.jpeg)

Sequence diagram (authentication)
![Login Interface](images/sequence%20diag.jpeg)

Sequence diagram (Seneral)
![Login Interface](images/sequence%20diag%20general.jpeg)

---

## Implementation

### Development Environment

#### Hardware
- **Processor**: Intel(R) Core (TM) i5-6198 CPU @ 2.30GHz 2.40GHz
- **RAM**: 8.00 GB
- **Hard Drive**: 1 TB HDD
- **Graphics Card**: Nvidia Geforce 920 MX
- **OS**: Ubuntu 20.04

#### Software
- **IDE**: IntelliJ IDEA
- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: PostgreSQL
- **API Testing**: Postman

---

## Application Presentation

### Interface Examples

#### Login Interface
![Login Interface](images/cap%20login.jpeg)

#### Home Page
![Home Page](images/cap%20home.jpeg)

#### Home Page
![Home Page](images/cap%20home.jpeg)

#### Search by Operation
![Search by Operation](images/cap%20search%20.jpeg)




---

## Conclusion

The internship at Sagemcom provided a valuable experience, allowing the development of a traceability application for production processes. The project enhanced technical skills in frameworks like Spring Boot and Angular and improved professional skills through real-world business integration.

---

## References

- **Sagemcom**: [Sagemcom Website](https://www.sagemcom.com/fr)
- **Spring Boot**: [Spring Boot Documentation](https://spring.io/)
- **Angular**: [Angular Material](https://material.angular.io)
- **Postman**: [Postman](https://www.postman.com)
- **PostgreSQL**: [PostgreSQL Documentation](https://www.postgresql.org)
