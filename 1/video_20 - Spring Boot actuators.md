Spring boot actuator
* add the dependency to the POM file
* Endpoints are prefixed with : **/actuator**

Health Endpoint:

* **health** check the status of our application
* **/health** is used by monitoring application to check if app is up or down

 Exposing Endpoints:
 - By default, only **/health** is exposed
-  **/info** endpoint can provide info about our application
- To expose **/info**

Info Endpoint
**/info ** gives information about our application
- Update **application.properties** within the app info
