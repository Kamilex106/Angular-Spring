# E-Commerce Angular + Spring Boot

## Project Description

An e-commerce application built using Angular (frontend) and Spring Boot (backend). The project allows browsing products, adding them to cart, managing the cart, and placing orders. The system also includes user authentication using Okta.

## Features

- Product list with ability to browse by category
- Product details
- Product search
- Shopping cart
- Checkout and order process
- User login and registration
- Member page (accessible only to logged-in users)

## Technologies

### Frontend
- Angular 
- TypeScript
- Bootstrap (ng-bootstrap)
- Okta (authentication)
- Angular Reactive Forms

### Backend
- Spring Boot
- Spring REST API
- Java

## Installation and Setup

### Prerequisites
- Node.js and npm
- Angular CLI
- Java JDK 21+
- Maven

### Frontend
1. Navigate to the frontend directory
2. Install dependencies:
```
npm install
```
3. Run the application:
```
ng serve
```
4. The application will be available at: `http://localhost:4200/`

### Backend
1. Navigate to the backend directory
2. Build the project:
```
mvn clean install
```
3. Run the application:
```
mvn spring-boot:run
```
4. The API will be available at: `http://localhost:8080/api`

## Okta Configuration

To configure Okta authentication:
1. Create an account on the Okta platform
2. Create an OIDC application
3. Configure the `my-app-config.ts` file with appropriate credentials

Sample user:
login: `kamil@test.com`
password: `ShopUser123@`



