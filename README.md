

CRM Lead Management System

This is a simple CRM Lead Management System built using Spring Boot.  
I created this project to practice backend development and understand how CRM systems like Salesforce manage leads, activities and users.

Right now this version is just the basic setup of the backend with a working Spring Boot structure and a health check API.  
I will keep improving this project by adding real CRM features.

---

Tech Used
- Java 17  
- Spring Boot  
- Maven  
- Tomcat (embedded)  

What is working now
- Spring Boot application runs without issues  
- Health check API to verify the service  

Health Check Endpoint


This is a minimal Spring Boot project that **builds and runs successfully**.

How to run

```bash
mvn spring-boot:run
```

Then open:

- http://localhost:8080/api/health
