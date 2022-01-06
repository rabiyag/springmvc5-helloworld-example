
# Spring MVC 5 Hello World Example

This is a simple **Spring MVC 5** "Hello World" project to demonstrate the basic configuration and setup of a Spring MVC application. It includes a simple controller that returns a greeting message, with JSP used for the view layer.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [Usage](#usage)

## Features
- Basic Spring MVC 5 configuration
- Simple controller for handling requests
- JSP view that displays a "Hello World" message

## Technologies Used
- **Spring MVC 5**
- **JSP** (Java Server Pages)
- **Java** (JDK 8 or higher)

## Project Structure
```
src/main/java
    ├── config          # Spring configuration
    ├── controller      # HelloController for handling requests
src/main/webapp
    ├── WEB-INF
    │   ├── jsp         # JSP views
    │   └── web.xml     # Application deployment descriptor
```

## Prerequisites
- **JDK 8** or higher
- **Maven** for dependency management

## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/rabiyag/springmvc5-helloworld-example.git
   cd springmvc5-helloworld-example
   ```

2. **Build the project with Maven**:
   ```bash
   mvn clean install
   ```

## Running the Application
1. **Run the application** using Maven:
   ```bash
   mvn spring-boot:run
   ```

2. **Access the application**:
   - Open a browser and go to `http://localhost:8080/hello`.

## Usage
- Visiting the `/hello` endpoint will display a simple "Hello World" message rendered by the JSP view.

