No hard code values
Read values from .properties file

**src/main/resources/application.properties**  - Standard properties file
Any custom properties can be defined in this file



**DEVELOPMENT PROCESS**
1. Define custom properties in application.properties
2. Inject properties into Spring Boot application using @Value


```
coach.name="Micky Mouse"  
team.name="The mickey mouse club"
```

FunRestController

```
@Value("${coach.name}")  
private String coachName;  
  
@Value("${team.name}")  
private String teamName;
```
