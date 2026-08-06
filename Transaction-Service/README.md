# Transaction Service

## Introduction
The Transaction Service is a microservice responsible for managing bank transactions. It provides APIs for creating, retrieving, and listing transactions.

## Table of Contents
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
    - [Spring Boot](#spring-boot)
    - [Spring Data JPA](#spring-data-jpa)
    - [MySQL](#mysql)
    - [Spring Cloud](#spring-cloud)
    - [Eureka Server](#eureka-server)
    - [Feign Client](#feign-client)
    - [Lombok](#lombok)
- [API Endpoints](#api-endpoints)
    - [Create Transaction](#create-transaction)
    - [Get Transaction Details](#get-transaction-details)
    - [List Transactions](#list-transactions)
- [Error Handling](#error-handling)
- [Security](#security)
- [Configuration](#configuration)
- [Monitoring](#monitoring)
- [Logging](#logging)
- [Testing](#testing)
- [Build and Deployment](#build-and-deployment)

## Project Structure
The project structure of the Transaction Service is as follows:
```
Transaction Service
|-- src
|   |-- main
|   |   |-- java
|   |   |   `-- com
|   |   |       `-- example
|   |   |           `-- transactionservice
|   |   |               |-- controller
|   |   |               |