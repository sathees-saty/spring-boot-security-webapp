# spring-boot-security-webapp
Securing a Web Application

Steps:
Open Spring Tool Suite 4
Create Spring Starter Project
Select Spring Web , Thymeleaf, Spring Security
Project created
Check pom.xml for the spring-boot-starter-security, thymeleaf-extras-springsecurity6 and spring-security-test dependency.
Create MvcConfig class - configures Spring MVC in the application
Create WebSecurityConfig class - ensures that only authenticated users allowed. We are using in memory user details.
SecuringWebApplication class - The Spring Initializr creates an application class for us.
Create home.html – to navigate to login page - http://localhost:8080/
Create login.html – to login
Create hello.html – to Sign out
Right click Application class and run as Spring Boot App it starts tomcat server.
Type http://localhost:8080/ and access the web app

**Architecture:
**
![Spring-Security-Architecture](https://github.com/sathees-saty/spring-boot-security-webapp/assets/65384711/b1241d1d-270d-4b89-b02b-214ed4e98a31)

