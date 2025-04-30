## Setup First Project
Untuk membuat project baru Spring Boot dapat dilakukan di website https://start.spring.io/

![Screenshot 2025-05-01 at 03 57 29](https://github.com/user-attachments/assets/24d3b01b-b82d-4acd-b1b7-8b8444ffb0aa)

Setup java version, disini menggunakan openjdk17

![Screenshot 2025-05-01 at 03 57 41](https://github.com/user-attachments/assets/c62d76c7-04f3-4371-9b10-9ef8ff8aa091)

## Running Project Spring Boot
Preparation tools, menggunakan IntilliJ IDEA CE (community edition)

https://github.com/user-attachments/assets/44d15f3e-6c2e-4434-b3a1-ca4f89db4fcb

```.sh
./mvnw spring-boot:run
```

Setup database connection

```.properties
spring.application.name=Restfull API Java Spring Boot
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=!!&21adi
spring.datasource.url=jdbc:mysql://192.168.191.64:3306/db_sakusama
spring.datasource.type=com.zaxxer.hikari.HikariDataSource
spring.datasource.hikari.minimum-idle=10
spring.datasource.hikari.maximum-pool-size=50
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.community.dialect.MySQLLegacyDialect
spring.jpa.properties.hibernate.transaction.jta.platform=org.hibernate.engine.transaction.jta.platform.internal.BitronixJtaPlatform
server.port=8098
```
