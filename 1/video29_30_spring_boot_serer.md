**Spring Boot Properties**

Server port, context path, actuator, security, etc
Spring has over 1000 properties

Spring Boot properties are grouped into following categories
1. Core
2. Web 
3. Security
4. Data
5. Actuator
6. Integeration
7. DevTools
8. Testing


**Core Properties:**

```
# Log level security mapping
logging.level.org.springframework=DEBUG
logging.level.org.hivernate=TRACE
logging.level.org.luv2code=INFO

# Log file name
logging.file.name=my-crazy-stuff.log
logging.file.path=C://myapps/demo
```


**Web Properties:**

```
# HHTP server port
server.port = 7070

#Context path of the application
server.servlet.context-path=/my-silly-app

# Default session time out
server.servlet.session.timeout=15m
```


**Actuator Properties:**

```
# Endpoints to include by name or wildcard
management.endpoints.web.exposure.include=*

# Endpoints to exclude by name or wildcard
management.endpoints.web.exposure.include=beans,mapping
```


**Security Properties**

```
# Default user name
spring.security.user.name=admin

# Password for default user
spring.security.user.password=admin
```


**Data Properties**

```
# JDBC URL of the databases
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce

# Login username of the dataase
spring.datasource.username=scott

# Login password of the database
spring.datasource.password=tiger
```


**Server Properties**

```
# Change Spring Boot server port  
server.port=8080  
  
# Change context path of the application  
# All requests should have a prefix of mycoolapp  
server.servlet.context-path=/mycoolapp
```

