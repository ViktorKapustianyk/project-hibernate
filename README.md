# RPG Admin Console with Hibernate Repository

This project serves as an alternative implementation of the **RPG Admin Console's repository layer**, utilizing **Hibernate** as the primary data storage solution. The primary aim is to present a more realistic and scalable solution by incorporating a **relational database**.

## Steps Completed

1. **Environment Setup:**
   - Utilized **Java 8**, **Maven**, **MySQL 8**, and recommended the use of **IntelliJ IDEA**.

2. **Adding Dependencies:**
   - Updated dependencies in the `pom.xml` file:
     - **MySQL Connector** version 8.0.30.
     - **Hibernate Core** version 5.6.11.Final.

3. **Database Creation:**
   - Executed a script to create the `rpg` schema in **MySQL Workbench**.

4. **Application Configuration:**
   - Added database connection settings to the `application.properties` file.

5. **Using Hibernate:**
   - Introduced a **SessionFactory** field in the `PlayerRepositoryDB` class to work with **Hibernate**.
   - Implemented methods to interact with data using **Hibernate**.
   - Enabled **SQL query logging** using **P6Spy**.

6. **Testing and Launch:**
   - Conducted thorough testing of all methods for interacting with the database.
   - Successfully launched the project, providing **RESTful endpoints** for CRUD operations.

## Technologies and Tools

- **Java 8:** Used for application development.
- **Maven:** Employed for managing dependencies and building the project.
- **MySQL 8:** A **relational database** for storing character information in RPGs.
- **Hibernate:** A database framework providing **object-relational mapping (ORM)**.
- **IntelliJ IDEA:** Recommended development environment for the project.
- **P6Spy:** **SQL query logging** tool utilized to track running queries in the application.

