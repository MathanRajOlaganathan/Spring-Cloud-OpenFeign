# **Spring Cloud OpenFeign – a declarative REST client**

> The Feign is a declarative web service (HTTP client) developed by Netflix. Its aim is to simplify the HTTP API clients. It is a Java to HTTP client binder. If you want to use Feign, create an interface, and annotate it. It provides pluggable annotation support, including Feign annotations and JAX-RS annotations.

* Spring Cloud OpenFeign provides OpenFeign integrations for Spring Boot apps through auto-configuration and binding to the Spring Environment. Without Feign,
* To use the Feign, we need to add _spring-cloud-starter-openfeign_ dependency in the pom.xml file.
* It also integrates with the Ribbon (client-side load balancing framework). No need to explicitly manage3
the load.
* To enable the Feign to scan the clients by adding the annotation @EnableFeignClients 

* The request we are sending uses Feign. Feign is a REST Service client. 
* Feign can call the RESTful web services easily. When we use the RestTemplate to call the 
RESTful service, it creates duplication of code that talks to RESTful services.
  
* When we define Feign, we need only to define a proxy and define a single method into it.
 Feign helps us to simplify client code to talk to the RESTful web services.