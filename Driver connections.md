# Spring Boot DB driver connections

### MySQL

> Maven dependency 

```xml
<!--pom.xml-->
<dependency>
	<groupId>mysql</groupId>
	<artifactId>mysql-connector-java</artifactId>
	<scope>runtime</scope>
</dependency>
```

> application.properties

```properties
spring.datasource.driver-class-name =com.mysql.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://${MYSQL_HOST:localhost}:3306/db_example
spring.datasource.username=springuser
spring.datasource.password=ThePassword
#spring.jpa.show-sql: true
```

