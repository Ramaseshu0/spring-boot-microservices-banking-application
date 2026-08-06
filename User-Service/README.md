# User Service

## Introduction
The User Service is a microservice responsible for managing user information. It provides APIs for creating, retrieving, updating, and deleting user details.

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
    - [Create User](#create-user)
    - [Get User Details](#get-user-details)
    - [Delete User](#delete-user)
    - [Update User](#update-user)
    - [List Users](#list-users)
- [Error Handling](#error-handling)
- [Security](#security)
- [Configuration](#configuration)
- [Monitoring](#monitoring)
- [Logging](#logging)
- [Testing](#testing)
- [Build and Deployment](#build-and-deployment)
- [Maintainer](#maintainer)

## Project Structure
The project structure of the User Service is as follows:
```
User Service
|-- src
|   |-- main
|   |   |-- java
|   |   |   `-- com
|   |   |