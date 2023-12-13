**POM File:**

Project Object Model file - used for configuration for project 
Located at root dir of maven project


It contains *
project meta data - Name of project, version, output file type like JAR, WAR, etc
dependencies: spring , hibernate , etc
plugins : additional custom tasks like generate Junit test reports




```
<project> 
```

**Dependency Coordinates**
* GroupID
* Artiffact ID
* Version *<optional> 
This is also referred to as GAV


How to find Dependency Coordinates

1. Visit the project page (Spring.io, hibernate.org, etc)
2. Visit http://search.maven.org <easiestapproach>