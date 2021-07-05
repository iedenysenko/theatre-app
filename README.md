# Theatre application
![theatre_logo](theatre_logo.jpg)

Simple REST application that represents the work of the theatre, where user can buy tickets for a specific performance session (definite performance in definite theatre stage). To buy tickets user firstly adds them to the shopping cart and then completes an order. There are authentication and authorization. User can have different roles: USER, ADMIN or no role.

## Guest can:
* register
* view all available performance sessions
* view all theatre stages
* view all performances

## Admin can:
* add new theatre stages
* add new performance
* add new performance session
* delete performance session
* update performance session
* find user by email

## User can:
* add tickets to shopping cart
* view all the tickets in shopping cart
* complete the order
* view a history of all the orders

## Technologies
* Spring - Core / MVC / Web / Security
* Hibernate
* DataBase - MySQL
* Packaging - Apache Maven
* Tomcat

## Setup
**1.** Clone this project

**2.** Configure Tomcat Server

**3.** Setup new connection in "src/main/resources/db.properties" with:
- USERNAME: "your username"
- PASSWORD: "your password"
- URL: jdbc:mysql://xxxx:yyyy/kkkk?serverTimezone=UTC , where:
    * xxxx - host name,
    * yyyy - port,
    * kkkk - database name

**4.** Run project

**5.** Admin and User will be added to your database when program start. You can log in as: Admin: (name: "james@gmail.com", password:"1234"), or User: (name: "alex@gmail.com", password:"1234")
