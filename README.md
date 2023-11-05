# School Management System with Spring Boot

This project is a School Management System built with Spring Boot, Maven, Hibernate, JPA, and SQL database. It provides essential functionality to create, read, update, and delete (CRUD) students, roles, and filieres. The project also includes Swagger and Postman for easy testing and interaction with the API.

## Technologies Used
- Spring Boot
- Maven
- Swagger
- Hibernate
- JPA
- SQL Database
- Postman

## Project Features
1. CRUD operations for students, roles, and filieres.
2. Utilize Swagger for easy testing and API interaction.

## Screenshots
### Data Base
<img width="579" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/8c8f7000-1cc9-43f7-81cc-50d89a9a5b00">

### Swagger Student API 
<img width="942" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/532a3d95-5421-493f-be81-2c1ef3e23cb4">

<img width="917" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/c15bb29d-9771-4ebc-8108-ede6344dd50f">

### Student display with Postman
<img width="638" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/92f2c3aa-f9a6-4ed5-8a5e-d5e52a3d19f1">

### Find by id example
<img width="632" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/6f5dff8c-67fd-413f-bb69-d6d74d1c5196">


#### Student JSON
<img width="387" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/9d252433-9dd8-4ffe-8a4f-73bd4022d00b">

### Swagger Filiere API 
<img width="935" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/1b77ea44-6a91-4e72-9a11-23f896cfeeea">

<img width="861" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/2b4aa990-ddcc-4212-a7bc-fc7373234df9">

### Filiere display with postman
<img width="633" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/df214617-cb02-4c6d-91b1-9eb316397196">

### Delete example
<img width="625" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/72f72fb9-83dc-4b23-afc4-33306591e839">


#### Filiere JSON
<img width="300" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/4286363a-da43-4b93-84fa-588b4a809fb8">


### Swagger Role API 
<img width="942" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/8f77a34a-3829-47ab-815b-6f0986239661">

<img width="861" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/5431d4ef-4676-4f00-b22b-9911f96d89c6">

### Roles display with postman
<img width="639" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/4cbb1f3c-ae2c-48cd-b2e8-92c82a6526d8">

### Update example
<img width="626" alt="image" src="https://github.com/MaskedFezz/tpSpringBoot/assets/130797834/27fc3a82-bacb-433e-bbb5-e26b2f9ac2c3">

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

## How to Run the Project
1. Clone this project to your computer.
2. Configure the database connection in the `application.properties` file.
3. Run the project using Maven or your favorite Spring Boot IDE.
4. Access Swagger to test the API: `http://localhost:8088/swagger-ui/index.html`

## Authors
- [Mohamed Fezzazi](https://github.com/MaskedFezz) (Email address: mohamedfezzazi22@gmail.com)
- [Mohamed Lachgar ](https://github.com/lachgar) (Professor)

