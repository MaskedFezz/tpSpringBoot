# School Management System with Spring Boot

This project is a School Management System built with Spring Boot, Maven, Hibernate, JPA, and SQL database. It provides essential functionality to create, read, update, and delete (CRUD) students, roles, and filieres. The project also includes Swagger for easy testing and interaction with the API.

## Technologies Used
- Spring Boot
- Maven
- Swagger
- Hibernate
- JPA
- SQL Database

## Project Features
1. CRUD operations for students, roles, and filieres.
2. Utilize Swagger for easy testing and API interaction.

## Screenshots
### Data Base
<img width="579" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/8c8f7000-1cc9-43f7-81cc-50d89a9a5b00">

### Swagger Student API 
<img width="942" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/532a3d95-5421-493f-be81-2c1ef3e23cb4">

#### Student JSON
<img width="387" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/9d252433-9dd8-4ffe-8a4f-73bd4022d00b">

### Swagger Filiere API 
<img width="935" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/1b77ea44-6a91-4e72-9a11-23f896cfeeea">

#### Filiere JSON
<img width="300" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/4286363a-da43-4b93-84fa-588b4a809fb8">


### Swagger Role API 
<img width="942" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/8f77a34a-3829-47ab-815b-6f0986239661">

#### Role JSON
<img width="305" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/5f0fa5e9-e8d9-4d32-8fc7-de88cd5ddcaa">

## Project Structure
The project is divided into packages that represent different aspects of the application:

- `ma.projet.demo`: Main application package.
- `ma.projet.controller`: Controllers for managing students, roles, and filieres.
- `ma.projet.entities`: Model classes for students, roles, and filieres.
- `ma.projet.repositories`: JPA repositories for database operations.
- `ma.projet.service`: Service classes for handling business logic.
- `ma.projet.dao`: IDao interface.

## System Requirements
- Java 17
- Maven
- SQL Database
- Swagger for testing and interaction

## How to Run the Project
1. Clone this project to your computer.
2. Configure the database connection in the `application.properties` file.
3. Run the project using Maven or your favorite Spring Boot IDE.
4. Access Swagger to test the API: `http://localhost:8088/swagger-ui/index.html`

## Authors
- [Mohamed Fezzazi](https://github.com/MaskedFezz) (Email: mohamedfezzazi22@gmail.com)
- [Mohamed Lachgar ](https://github.com/lachgar) (Professor)

