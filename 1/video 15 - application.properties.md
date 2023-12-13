By default, Spring Boot will load properties from application.properties

**src/resource/application.properties** is the location of the file



```
#
# application.properties file
#

#configure my props
coach.name=Mickey Mouse
team.name=The Mouse Team
```

```
@RestController 

public class FunRestController {
	@Value("${coach.name}")
	private String coachName;

	@Value("${team.name}")
	private String teamName;
}
```


**STATIC CONTENT**

**src/main/static** - Spring Boot will load static resource from this directory. Eg: CSS, JS, images, etc

Do not use **src/main/webapp** dir if the application is packaged as JAR
Although this is a standard Maven directory, it only works with WAR packaging. It is **silently ignored** by most build tools if you generate a JAR.

**TEMPLATES**
Spring Boot includes auto configuration for following template engines:
- Freemarker
- Thymeleaf
- Mustache

**UNIT TESTS**
