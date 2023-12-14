Add spring boot security

```
#Add a dependency to add security
```

The default username and password can be overwritten by adding the information in **src/main/resources/application.properties**

```
spring.security.user.name=admin
spring.security.user.password=admin
```

Spring Security can be customised for Spring Boot Actuator
We can use a database for roles, encrypted passwords, etc



We can also exclude endpoints.

For eg: to exclude **/health** and **/info**

 **src/main/resources/application.properties**
 
```
#Exclude endpoints
management.endpoints.web.exposure.exclude=health,info
```

