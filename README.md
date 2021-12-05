# employeemanager-backend
REST API for the employeemanager application

## How was did build it?
This REST API was built using Java, specifically Spring Boot, Spring Data and also using MySQL.

## Goals completed
* Implement the REST API for the employeemanager application using SpringBoot and its dependencies like JPA and Hibernate.

## Observations
* You need to have a application.properties file in the path /src/main/resources/application.properties of your project. The variables are:  
    > spring.datasource.url=jdbc:mysql://yourserver/yourdatabase  
    > spring.datasource.username=yourusername    
    > spring.datasource.password=yourpassword    
    > spring.jpa.show-sql=true    
    > spring.jpa.hibernate.ddl-auto=update    
    > spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5Dialect  

* To run the rest api, open a terminal and execute the following command:  
    > mvn spring-boot:run  

## Tech
* Java
* Spring Boot
* Spring Data
* Hibernate
* JPA
* MySQL