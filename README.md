# Cat Marketplace 😸
A marketplace application where users (cats) can browse, list, and purchase items.
This project uses a Spring Boot backend and a Vue.js frontend, with PostgreSQL as the database. 

## 🟢 Prerequisites
- Node.js v20 (ensure `npm` is available)
- Java v22
- PostgreSQL (installed and running locally on default port 5432)
- IntelliJ IDEA or any Java IDE to run the Spring Boot application

## 🟢 Database Setup
- Install PostgreSQL if not already installed. [PostgreSQL Installation Guide](https://www.postgresql.org/download/)
- Create a database named `cat_marketplace`. You can use the following command:
```
CREATE DATABASE cat_marketplace
```
## 🟢 Backend - SpringBootMarket
- Update the credentials in `src/main/resources/application.properties` if your PostgreSQL username and 
password differ (default values below):
```
spring.datasource.username=postgres
spring.datasource.password=123456789
```

- Run the Spring Boot application using IntelliJ or from the command line:
```
./gradlew bootRun
```

## 🟢 Frontend - VueJsMarket
- Navigate to the `vuejsmarket` folder in your terminal and run the following 
commands to install dependencies and start the development server:
```
npm install
```
```
npm run dev
```