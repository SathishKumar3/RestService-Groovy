
**Technology Used :**

 - Spring boot 2.0.2
 - Java 1.8.0_171 
 - Junit,Mokito 
 - Mongo DB 
 - Maven 
 
**Application set up:**

 - Java 1.8.0_171 
 - Install Mongo DB, default port:27017   
 - Maven 
 - Postman (any rest cleint)
 
 
**Swagger Documentation path:**

https://documenter.getpostman.com/view/534845/RW87p9pT

**Postman document of Test cases:**

https://documenter.getpostman.com/view/534845/RW87p9pT
 
**To execute Test cases and Integration Test:**

 ```sh
> mvn clean test
```

**To start application:**
 
 ```sh
>mvn spring-boot:run -Dspring.profiles.active=dev -> Tomcat starts on default port 8080
```
**Features:**
- Basic Authentication:
    - Get method to fecth the product info, will be access to all.
    - Post method to update price info, will be secured. (Admin/Admin).
- Logging:
    - Used logback for logging, 
    - Followed logging best pratices helps troubleshooting and also helps monitoring ,creating metrices and dashboards.
    - Maintaing key values and Transaction id for each request.  
 - RestService calls: 
    - RestService template acts as a wrapper class for any rest service calls.    
- Documentation:
    - Code has been completely documented through unit test case and integration test.
 
 
 





