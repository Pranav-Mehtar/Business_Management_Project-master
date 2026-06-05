## Technologies Used

* Spring Boot – Backend framework for building Java-based web applications.
* Thymeleaf – Server-side Java template engine for dynamic HTML generation.
* PostgreSQL – Relational database management system for data storage.
* Spring Security – Authentication and authorization.
* Maven – Dependency management and build tool.
* IDE/Tool – IntelliJ IDEA.

---


```

### . Open the Project in IntelliJ IDEA

* Open IntelliJ IDEA.
* Select **Open**.
* Browse to the project folder.
* Open the project as a Maven project.
* Wait for Maven dependencies to download.

### . Configure the Database

Create a PostgreSQL database and update the `application.properties` file.

### . Run the Application

Run the main class:

```java
BusinessProjectApplication.java
```

Or click the **Run** button in IntelliJ IDEA.

### . Open the Application

```
http://localhost:8080
```

### . Create Initial Admin User

* Tables will be created automatically on startup.
* Insert an admin record manually into the database.
* Use the admin credentials to log in.

---

## Database Configuration (PostgreSQL)

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/business_management_db
spring.datasource.username=postgres
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

server.port=8080
```
