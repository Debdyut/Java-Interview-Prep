# Spring Interview Questions
## Question Bank 1

1. <strong>What are the advantages of Spring Boot?</strong><br/>
    - It is bvery easy to develop Spring based applications using Java or Groovy.
    - It reduces a lot of development time and increases productivity.
    - It avoids writing lots of boilerplate code, annotations and XML configurations.
    - It is very easy to integrate Spring Boot application with its Spring ecosystem like Spring JDBC, Spring ORM, Spring Data, Spring Security, etc.
    - It follows "Opinionated Defaults Configuration" approach to reduce developer effort.
    - It provides Embedded HTTP servers like Tomcat, Jetty, etc. to develop and test our web applications very easily.

2. <strong>How security is provided by Spring boot?</strong><br/>

3. <strong>What is the default server used by Spring boot?</strong><br/>
    By default, Spring boot used Tomcat 7.

4. <strong>How to change the server port in spring boot?</strong><br/>
    Set `server.port` in application.properties (or other property files).

5. <strong>How to secure Rest API?</strong><br/>

6. <strong>What OAuth and how it functions?</strong><br/>
    OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

7. <strong>Differences between @Controller and @RestController.</strong><br/>
    The @Controller is a common annotation that is used to mark a class as Spring MVC Controller, while @RestController is a special controller used in RESTful web services and the equivalent of @Controller + @ResponseBody.