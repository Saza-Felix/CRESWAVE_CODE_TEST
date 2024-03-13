# Blogging Application

![Blogging Application](https://user-images.githubusercontent.com/105907169/209240082-4c5793e1-e72f-4778-bb9f-194bbdc4d3a1.jpg)

## Features 

 - The API implements Spring Security and JSON Web Token (J.W.T) for authentication, validation, and authorization of users and administrators.
 - The API includes functionality for pagination, sorting, and searching of data.
 - The API implements custom exception handling for all exceptions and validations.
 - The API utilizes custom request and response data transfer objects for all HTTP requests.
 - The API's primary objective is to provide a streamlined and user-friendly blogging experience for users.
 - Built on REST Architecture
 - Consumable by clients that support HTTP Protocol
 - Can be integrated with any application that supports REST API
 - Suitable for a wide range of use cases.

## Tech Stack

- JAVA
- SPRING
- SPRINGBOOT
- HIBERNATE
- MAVEN
- J.D.B.C
- MYSQL
- POSTMAN

## Dependencies

- JWT AUTHENTICATION
- SPRING SECURITY
- SPRING DATA JPA 
- SPRING BOOT DEVTOOLS
- SPRING WEB
- HIBERNATE
- MYSQL DRIVER
- VALIDATION
- LOMBOK
- MODEL MAPPER
- LOGGER



## User Functionalities

- **Authentication Management**

  - Endpoint for Sign Up
  - Endpoint for Sign In
  - Endpoint for Sign Out

- **Profile Management**

  - Endpoint for Updating User Information
  - Endpoint for Retrieving User Information
  - Endpoint for Deleting User Account

- **Post Management**

  - Endpoint for Creating Posts
  - Endpoint for Updating Posts
  - Endpoint for Retrieving Posts
  - Endpoint for Deleting Posts
  - Endpoint for Adding Comments to Posts
  - Endpoint for Updating Post Images
  - Endpoint for Retrieving Posts with Custom Pagination

- **Category Management**

  - Endpoint for Creating Categories
  - Endpoint for Updating Categories
  - Endpoint for Retrieving Categories
  - Endpoint for Deleting Categories

- **Searching & Sorting Posts**

  - Endpoint for Searching Posts by :
    - Title
    - Date
    - Category
  - Endpoint for Sorting Posts by :
    - Date
    - Popularity

- **User Search**

  - Endpoint for Searching Users by :
    - Name
    
## Administrator Functionalities    
  
- **Authentication Management**

  - Endpoint for Sign Up Other Admin Accounts
  - Endpoint for Sign In
  - Endpoint for Sign Out


- **Profile Management**
  - Endpoint for Deleting Admin Accounts

- **Post Management**
  - Endpoint for Retrieving Posts
  - Endpoint for Deleting Posts

- **Category Management**
  - Endpoint for Retrieving Categories
  - Endpoint for Deleting Categories

- **Comment Management**
  - Endpoint for Retrieving Comments
  - Endpoint for Deleting Comments



## Setting & Installation 

Install the Spring Tools Suite 
```bash
https://spring.io/tools
```

Install MySQL Community Server

```bash
https://dev.mysql.com/downloads/mysql/
```

Clone the Project

```bash
git clone https://github.com/Saza-Felix/CRESWAVE_CODE_TEST
```

Open MySQL Server
```bash
Create a New Database in SQL: "blog_db" 
```
Admin Login Details For Your Database

```bash
{
    "password": "creswave_code_test",
    "username": "root"
}
```




## Run Locally


Go to the Project Directory

```bas
Open the Blog Application Folder with S.T.S
```

Go to **src/main/resources > application.properties** & change your username and password (MySQL server username & password)

```bash
spring.datasource.username="username"

spring.datasource.password="password"
```

To change the **Server Port**

```bash
server.port=8088
```

Go to **com.masai package > Blog_Application.java**

```bash
Run as Spring Boot App !
```

## Base Url
```bash
http://localhost:8088
```
"# CRESWAVE_CODE_TEST" 
