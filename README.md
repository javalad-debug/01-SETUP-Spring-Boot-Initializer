# SETUP Spring Boot Initializer

Foobar is a Python library for dealing with word pluralization.
We are going to setup a Spring Boot Initializer of a Demo project for Spring Boot Employee Management System



[Spring Boot Initializer](https://start.spring.io/)

- 1 - Under project select `Maven`.
- 2 - Under Language select `Java`.
- 3 - Under SpringBoot (version), leave the default option `3.4.5`.

## PROJECT METADATA
- 4 - Under Group, you can give any group you want `net.javaguides`
- 5 - Under Artifact give `ems-backend`, because here we have employee management system (EMS) and then backend 
- 6 - Under Name give `ems-backend`
- 7 - Under Description give `Demo project for Spring Boot Employee Management System`
- 8 - Under Package Name give `net.javaguides.ems`
- 9 - Under Packaging select `jar`
- 10 - Under Java select `17`
- 11 - Click `Add dependencies` type `web` select `Spring Web`

**Note:** Whenever you want to develop the Spring Boot RESTful web services make sure you choose `Spring Boot Web` or Spring Boot starter web dependencies. Spring Boot Web uses Apache Tomcat as the default embedded container.

- 12 - Click `Add dependencies` type `jpa` select `Spring Data JPA`

**Note:** This is required to run the Repository Layer

- 13 - Click `Add dependencies` type `PostgreSQL` select `PostgreSQL Driver`

**Note:** This allows Java program to connect to a PostgreSQL database, using standard database independent java code 

- 14 - Click `Add dependencies` type `Lombok` select `Lombok`

**Note:** This is a java annotation library which helps to reduce boilerplate code

- 15 - Click `GENERATE` to generate the Spring Boot application as a zip file.





## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

**
